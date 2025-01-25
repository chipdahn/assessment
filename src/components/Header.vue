<script setup>
import BrandLogo from './icons/BrandLogo.vue';
import IconBell from './icons/IconBell.vue';
import IconMenu from './icons/IconMenu.vue';
import IconMessage from './icons/IconMessage.vue';

</script>

<template>
    <div>
        <header>
            <div class="header-menu-logo">
                <div class="menu-container">
                    <IconMenu/>
                </div>
                <div>
                    <BrandLogo/>
                </div>
                <div class="branch-container">
                    <span>Branch</span>
                    <span class="branch-arrow">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M8.29201 10.293C8.1052 10.4819 8.00043 10.7368 8.00043 11.0025C8.00043 11.2682 8.1052 11.5231 8.29201 11.712L11.231 14.677C11.449 14.892 11.731 14.999 12.01 14.999C12.289 14.999 12.566 14.892 12.779 14.677L15.709 11.722C15.8956 11.533 16.0002 11.2781 16.0002 11.0125C16.0002 10.7469 15.8956 10.492 15.709 10.303C15.6172 10.2098 15.5077 10.1358 15.387 10.0853C15.2664 10.0348 15.1368 10.0088 15.006 10.0088C14.8752 10.0088 14.7457 10.0348 14.625 10.0853C14.5043 10.1358 14.3948 10.2098 14.303 10.303L12.005 12.62L9.69801 10.293C9.60597 10.2002 9.49646 10.1265 9.3758 10.0762C9.25514 10.0259 9.12572 10.0001 8.99501 10.0001C8.86429 10.0001 8.73487 10.0259 8.61421 10.0762C8.49355 10.1265 8.38404 10.2002 8.29201 10.293Z" fill="#44546F"/>
                        </svg>
                    </span>
                </div> 
            </div>
            <div class="user-option">
                <div class="notification-container">
                    <IconBell/>
                </div>
                <div>
                    <IconMessage/>
                </div>
                <div class="user-profile">
                    <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                    <circle cx="16" cy="16" r="12" fill="url(#pattern0_594_1809)"/>
                    <defs>
                    <pattern id="pattern0_594_1809" patternContentUnits="objectBoundingBox" width="1" height="1">
                    <use xlink:href="#image0_594_1809" transform="scale(0.0078125)"/>
                    </pattern>
                    <image id="image0_594_1809" width="128" height="128" xlink:href="data:image/png;base64,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"/>
                    </defs>
                    </svg>
                </div>
            </div>
        </header>
    </div>

</template>

<style scoped>

header {
    height: 50px;
    display: flex;
    align-items: center;
    padding: 0.5rem 0.5rem;
    border-bottom: 1px solid #091E4224;
    justify-content: space-between;
}

header div {
    height: 100%;
}

img {
    height: 100%;

}

.menu-container {
    cursor: pointer;
    display: flex;
    align-items: center;
}

.header-menu-logo {
    display: flex;
    gap: 14px;
    align-items: center;
    justify-content: center;

}

.branch-container {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1rem 1rem;
    background-color: #091E420F;
    font-family: 600;
    gap: 24px;
    border-radius: 6px;
    font-size: 14px;
    margin-left: 35px;
}

.branch-container span {
    display: flex;
    align-items: center;
    color: #172B4D;
}


.size-6 {
    height: 1rem;
    width: 1rem;
}

.size-6-2 {
    height: 24px;
    width: 24px;
}

.user-option {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 14px;
}

.user-option div {
    display: flex;
    align-items: center;
}

.notification-container {
    position: relative;
}

.notification-container::before {
    content: '9+';
    font-size: 10px;
    background-color: #C9372C;
    position: absolute;
    top: -2px;
    right: -8px;
    color: white;
    padding: 1px 8px;
    border-radius: 50px;
    z-index: 7;
}

.user-profile {
    padding: 4px;
    border-radius: 999px;
}

</style>