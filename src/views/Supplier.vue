<script setup>
import IconSupplierLogo from '@/components/icons/IconSupplierLogo.vue';
import AuthenticatedLayout from '@/components/Layouts/AuthenticatedLayout.vue';
import IconFilter from '@/components/icons/IconFilter.vue';
import SearchInput from '@/components/LoginForm/SearchInput.vue';

const purchaseOrders = [
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },
    {
        orderNumber: 'RHPO-1651244214',
        supplierName: 'Healthcare',
        type: 'Trade',
        date: '5/21/2024',
        total: '₦2,055,043.00',
        quantity: '93',
        quantityReturned: '4',
        status: 'Approved',
    },

]

</script>

<template>
    <AuthenticatedLayout>
        <div class="supplier">
            <div class="supplier-option-container">
                <div class="supplier-options">
                    <div>
                        <span>
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M9.00501 10.995L13.598 6.40199C13.6896 6.30854 13.7988 6.23416 13.9193 6.18318C14.0398 6.13219 14.1692 6.10559 14.3001 6.10493C14.4309 6.10427 14.5606 6.12956 14.6816 6.17932C14.8026 6.22909 14.9126 6.30236 15.0051 6.39488C15.0976 6.48741 15.1709 6.59736 15.2207 6.71837C15.2704 6.83939 15.2957 6.96907 15.2951 7.09992C15.2944 7.23077 15.2678 7.36019 15.2168 7.48069C15.1658 7.6012 15.0915 7.7104 14.998 7.80199L11.098 11.702L14.998 15.602C15.1806 15.7883 15.2822 16.0391 15.2809 16.2999C15.2796 16.5607 15.1754 16.8105 14.991 16.995C14.8065 17.1794 14.5568 17.2836 14.2959 17.2849C14.0351 17.2862 13.7843 17.1846 13.598 17.002L9.00501 12.41C8.81753 12.2225 8.71222 11.9682 8.71222 11.703C8.71222 11.4378 8.81753 11.1835 9.00501 10.996V10.995Z" fill="#44546F"/>
                            </svg>

                        </span>
                        <span>back</span>
                    </div>
                    <div>
                        SUPPLIER'S DASHBOARD
                    </div>
                    <div >
                       <button class="action-button edit">
                            <span>
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" clip-rule="evenodd" d="M4.02001 19.23C3.9869 19.392 3.99447 19.5597 4.04205 19.718C4.08963 19.8764 4.17573 20.0205 4.29265 20.1374C4.40956 20.2543 4.55364 20.3404 4.71199 20.388C4.87034 20.4355 5.03802 20.4431 5.20001 20.41L9.01001 19.63L4.80001 15.42L4.02001 19.23ZM19.844 6.707L17.724 4.585C17.5381 4.39908 17.3173 4.2517 17.0743 4.15131C16.8314 4.05092 16.5709 3.9995 16.308 4C15.796 4 15.284 4.195 14.893 4.585L5.13601 14.343L10.086 19.293L19.843 9.535C20.218 9.15995 20.4286 8.65133 20.4286 8.121C20.4286 7.59068 20.218 7.08206 19.843 6.707H19.844Z" fill="white"/>
                                </svg>
                            </span>
                            <span>
                                Edit
                            </span>
                        </button> 
                        <button class="action-button">
                            <span>
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M5 14C6.10457 14 7 13.1046 7 12C7 10.8954 6.10457 10 5 10C3.89543 10 3 10.8954 3 12C3 13.1046 3.89543 14 5 14Z" fill="#44546F"/>
                                <path d="M12 14C13.1046 14 14 13.1046 14 12C14 10.8954 13.1046 10 12 10C10.8954 10 10 10.8954 10 12C10 13.1046 10.8954 14 12 14Z" fill="#44546F"/>
                                <path d="M19 14C20.1046 14 21 13.1046 21 12C21 10.8954 20.1046 10 19 10C17.8954 10 17 10.8954 17 12C17 13.1046 17.8954 14 19 14Z" fill="#44546F"/>
                                </svg>
                            </span>
                        </button>
                    </div> 
                </div>
            </div>
            <div class="supplier-container">
                <div class="supplier-details-container">
                    <div class="supplier-info">
                    <div class="supplier-logo">
                            <IconSupplierLogo/>
                        </div>
                        <div class="supplier-contact">
                            <div class="contact">
                                <h4>Supplier info</h4>
                                <div class="address-container">
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M2.66667 7.33333H4V10.6667H2.66667V7.33333ZM3.03733 2.592C3.20067 2.26533 3.63333 2 4.004 2H11.9953C12.366 2 12.7993 2.26533 12.962 2.592L14 4.66667H2L3.03733 2.592ZM2 4.66667H14V5.33333H2V4.66667ZM12 7.33333H13.3333V10.6667H12V7.33333ZM2 5.33333C2.09333 6.08533 2.72933 6.66667 3.5 6.66667C4.27067 6.66667 4.90667 6.08533 5 5.33333H2ZM5 5.33333C5.09333 6.08533 5.72933 6.66667 6.5 6.66667C7.27067 6.66667 7.90667 6.08533 8 5.33333H5ZM8 5.33333C8.09333 6.08533 8.72933 6.66667 9.5 6.66667C10.2707 6.66667 10.9067 6.08533 11 5.33333H8ZM11 5.33333C11.0933 6.08533 11.7293 6.66667 12.5 6.66667C13.2707 6.66667 13.9067 6.08533 14 5.33333H11ZM2.66667 10.6667H13.3333V12.6633C13.3342 13.0168 13.1947 13.3562 12.9454 13.6069C12.6961 13.8575 12.3575 13.9989 12.004 14H3.996C3.82089 13.9997 3.64754 13.9649 3.4859 13.8976C3.32426 13.8302 3.17749 13.7316 3.05401 13.6075C2.93052 13.4833 2.83275 13.336 2.76628 13.174C2.69982 13.012 2.66596 12.8384 2.66667 12.6633V10.6667Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p> Fidson Healthcare</p>
                                    </div>
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M8 14C6.48 14 4 8.20933 4 6C4 4.93913 4.42143 3.92172 5.17157 3.17157C5.92172 2.42143 6.93913 2 8 2C9.06087 2 10.0783 2.42143 10.8284 3.17157C11.5786 3.92172 12 4.93913 12 6C12 8.20933 9.52 14 8 14ZM8 8C8.25494 8 8.50738 7.94979 8.74292 7.85223C8.97845 7.75466 9.19246 7.61167 9.37273 7.4314C9.553 7.25113 9.696 7.03712 9.79356 6.80158C9.89112 6.56605 9.94133 6.31361 9.94133 6.05867C9.94133 5.80373 9.89112 5.55128 9.79356 5.31575C9.696 5.08022 9.553 4.86621 9.37273 4.68594C9.19246 4.50567 8.97845 4.36267 8.74292 4.26511C8.50738 4.16755 8.25494 4.11733 8 4.11733C7.48513 4.11733 6.99134 4.32187 6.62727 4.68594C6.2632 5.05001 6.05867 5.54379 6.05867 6.05867C6.05867 6.57354 6.2632 7.06733 6.62727 7.4314C6.99134 7.79547 7.48513 8 8 8Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p>4, Road 56, Lagos, Nigeria</p> 
                                    </div>
                                    
                                </div>  
                            </div>
                            <div class="contact">
                                <h4>Supplier info</h4>
                                <div class="address-container">
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M2.66667 7.33333H4V10.6667H2.66667V7.33333ZM3.03733 2.592C3.20067 2.26533 3.63333 2 4.004 2H11.9953C12.366 2 12.7993 2.26533 12.962 2.592L14 4.66667H2L3.03733 2.592ZM2 4.66667H14V5.33333H2V4.66667ZM12 7.33333H13.3333V10.6667H12V7.33333ZM2 5.33333C2.09333 6.08533 2.72933 6.66667 3.5 6.66667C4.27067 6.66667 4.90667 6.08533 5 5.33333H2ZM5 5.33333C5.09333 6.08533 5.72933 6.66667 6.5 6.66667C7.27067 6.66667 7.90667 6.08533 8 5.33333H5ZM8 5.33333C8.09333 6.08533 8.72933 6.66667 9.5 6.66667C10.2707 6.66667 10.9067 6.08533 11 5.33333H8ZM11 5.33333C11.0933 6.08533 11.7293 6.66667 12.5 6.66667C13.2707 6.66667 13.9067 6.08533 14 5.33333H11ZM2.66667 10.6667H13.3333V12.6633C13.3342 13.0168 13.1947 13.3562 12.9454 13.6069C12.6961 13.8575 12.3575 13.9989 12.004 14H3.996C3.82089 13.9997 3.64754 13.9649 3.4859 13.8976C3.32426 13.8302 3.17749 13.7316 3.05401 13.6075C2.93052 13.4833 2.83275 13.336 2.76628 13.174C2.69982 13.012 2.66596 12.8384 2.66667 12.6633V10.6667Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p> Fidson Healthcare</p>
                                    </div>
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M8 14C6.48 14 4 8.20933 4 6C4 4.93913 4.42143 3.92172 5.17157 3.17157C5.92172 2.42143 6.93913 2 8 2C9.06087 2 10.0783 2.42143 10.8284 3.17157C11.5786 3.92172 12 4.93913 12 6C12 8.20933 9.52 14 8 14ZM8 8C8.25494 8 8.50738 7.94979 8.74292 7.85223C8.97845 7.75466 9.19246 7.61167 9.37273 7.4314C9.553 7.25113 9.696 7.03712 9.79356 6.80158C9.89112 6.56605 9.94133 6.31361 9.94133 6.05867C9.94133 5.80373 9.89112 5.55128 9.79356 5.31575C9.696 5.08022 9.553 4.86621 9.37273 4.68594C9.19246 4.50567 8.97845 4.36267 8.74292 4.26511C8.50738 4.16755 8.25494 4.11733 8 4.11733C7.48513 4.11733 6.99134 4.32187 6.62727 4.68594C6.2632 5.05001 6.05867 5.54379 6.05867 6.05867C6.05867 6.57354 6.2632 7.06733 6.62727 7.4314C6.99134 7.79547 7.48513 8 8 8Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p>4, Road 56, Lagos, Nigeria</p> 
                                    </div>
                                    
                                </div>  
                            </div>
                            <div class="contact">
                                <h4>Supplier info</h4>
                                <div class="address-container">
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M2.66667 7.33333H4V10.6667H2.66667V7.33333ZM3.03733 2.592C3.20067 2.26533 3.63333 2 4.004 2H11.9953C12.366 2 12.7993 2.26533 12.962 2.592L14 4.66667H2L3.03733 2.592ZM2 4.66667H14V5.33333H2V4.66667ZM12 7.33333H13.3333V10.6667H12V7.33333ZM2 5.33333C2.09333 6.08533 2.72933 6.66667 3.5 6.66667C4.27067 6.66667 4.90667 6.08533 5 5.33333H2ZM5 5.33333C5.09333 6.08533 5.72933 6.66667 6.5 6.66667C7.27067 6.66667 7.90667 6.08533 8 5.33333H5ZM8 5.33333C8.09333 6.08533 8.72933 6.66667 9.5 6.66667C10.2707 6.66667 10.9067 6.08533 11 5.33333H8ZM11 5.33333C11.0933 6.08533 11.7293 6.66667 12.5 6.66667C13.2707 6.66667 13.9067 6.08533 14 5.33333H11ZM2.66667 10.6667H13.3333V12.6633C13.3342 13.0168 13.1947 13.3562 12.9454 13.6069C12.6961 13.8575 12.3575 13.9989 12.004 14H3.996C3.82089 13.9997 3.64754 13.9649 3.4859 13.8976C3.32426 13.8302 3.17749 13.7316 3.05401 13.6075C2.93052 13.4833 2.83275 13.336 2.76628 13.174C2.69982 13.012 2.66596 12.8384 2.66667 12.6633V10.6667Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p> Fidson Healthcare</p>
                                    </div>
                                    <div class="address">
                                        <div>
                                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M8 14C6.48 14 4 8.20933 4 6C4 4.93913 4.42143 3.92172 5.17157 3.17157C5.92172 2.42143 6.93913 2 8 2C9.06087 2 10.0783 2.42143 10.8284 3.17157C11.5786 3.92172 12 4.93913 12 6C12 8.20933 9.52 14 8 14ZM8 8C8.25494 8 8.50738 7.94979 8.74292 7.85223C8.97845 7.75466 9.19246 7.61167 9.37273 7.4314C9.553 7.25113 9.696 7.03712 9.79356 6.80158C9.89112 6.56605 9.94133 6.31361 9.94133 6.05867C9.94133 5.80373 9.89112 5.55128 9.79356 5.31575C9.696 5.08022 9.553 4.86621 9.37273 4.68594C9.19246 4.50567 8.97845 4.36267 8.74292 4.26511C8.50738 4.16755 8.25494 4.11733 8 4.11733C7.48513 4.11733 6.99134 4.32187 6.62727 4.68594C6.2632 5.05001 6.05867 5.54379 6.05867 6.05867C6.05867 6.57354 6.2632 7.06733 6.62727 7.4314C6.99134 7.79547 7.48513 8 8 8Z" fill="#091E42" fill-opacity="0.31"/>
                                            </svg>
                                        </div>
                                        <p>4, Road 56, Lagos, Nigeria</p> 
                                    </div>
                                    
                                </div>  
                            </div>
                        </div>
                        

                    </div>
                    <div class="supplier-purchase-details-container">
                        <div class="supplier-purchase-details">
                            <div class="purchase">
                                <div class="purchase-order-number">
                                    <div class="purchase-order">Purchase Order</div>
                                    <div class="purchase-number">40</div>
                                </div>
                                <div class="purchase-price">₦5,250,000</div>
                            </div>
                            <div class="purchase">
                                <div class="purchase-order-number">
                                    <div class="purchase-order">Purchase Order</div>
                                    <div class="purchase-number">40</div>
                                </div>
                                <div class="purchase-price">₦5,250,000</div>
                            </div>
                            <div class="purchase">
                                <div class="purchase-order-number">
                                    <div class="purchase-order">Purchase Order</div>
                                    <div class="purchase-number">40</div>
                                </div>
                                <div class="purchase-price">₦5,250,000</div>
                            </div>
                            <div class="purchase">
                                <div class="purchase-order-number">
                                    <div class="purchase-order">Purchase Order</div>
                                    <div class="purchase-number">40</div>
                                </div>
                                <div class="purchase-price">₦5,250,000</div>
                            </div>
                            <div class="purchase">
                                <div class="purchase-order-number">
                                    <div class="purchase-order">Purchase Order</div>
                                    <div class="purchase-number">40</div>
                                </div>
                                <div class="purchase-price">₦5,250,000</div>
                            </div>
                        </div>
                    </div>
                    
                </div>
                <div>
                   <div class="option">
                        <div>
                            Purchase Order
                        </div>
                        <div>
                            Invoice
                        </div>
                        <div>
                            Payment
                        </div>
                    </div>
                    <div class="table-container">
                        <div>
                            <div class="procurement-header-container">
                                <div>
                                    <h1 class="procurement-header">PURCHASE ORDER</h1>
                                </div>
                                <div class="actions">
                                    <div class="branch-container">
                                        <span>Page 1/6</span>
                                        <span class="branch-arrow">
                                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M8.29201 10.293C8.1052 10.4819 8.00043 10.7368 8.00043 11.0025C8.00043 11.2682 8.1052 11.5231 8.29201 11.712L11.231 14.677C11.449 14.892 11.731 14.999 12.01 14.999C12.289 14.999 12.566 14.892 12.779 14.677L15.709 11.722C15.8956 11.533 16.0002 11.2781 16.0002 11.0125C16.0002 10.7469 15.8956 10.492 15.709 10.303C15.6172 10.2098 15.5077 10.1358 15.387 10.0853C15.2664 10.0348 15.1368 10.0088 15.006 10.0088C14.8752 10.0088 14.7457 10.0348 14.625 10.0853C14.5043 10.1358 14.3948 10.2098 14.303 10.303L12.005 12.62L9.69801 10.293C9.60597 10.2002 9.49646 10.1265 9.3758 10.0762C9.25514 10.0259 9.12572 10.0001 8.99501 10.0001C8.86429 10.0001 8.73487 10.0259 8.61421 10.0762C8.49355 10.1265 8.38404 10.2002 8.29201 10.293Z" fill="#44546F"/>
                                            </svg>
                                        </span>
                                    </div>
                                    <SearchInput/>
                                    <button class="action-button filter">
                                        <span>
                                            <IconFilter/>
                                        </span>
                                        <span>
                                            Filter
                                        </span>
                                    </button>
                                    <button class="action-button filter">
                                        <span>
                                            <svg width="17" height="15" viewBox="0 0 17 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M4.25 1V14M4.25 14L1 10.75M4.25 14L7.5 10.75M12.375 14V1M12.375 1L9.125 4.25M12.375 1L15.625 4.25" stroke="#44546F" stroke-width="1.625" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </span>
                                        <span>
                                            Sort by
                                        </span>
                                    </button>
                                    <button class="action-button filter">
                                        <span>
                                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M3.00002 18C3.00002 18.552 3.44502 19 3.99302 19H20.007C20.138 18.9999 20.2676 18.9739 20.3885 18.9235C20.5094 18.8731 20.6191 18.7993 20.7114 18.7064C20.8036 18.6135 20.8766 18.5032 20.9262 18.382C20.9757 18.2608 21.0008 18.131 21 18V17H3.00002V18ZM3.00002 11H21V9H3.00002V11ZM3.00002 7H21V6C21 5.448 20.555 5 20.007 5H3.99302C3.86206 5.00013 3.73242 5.02613 3.61155 5.07652C3.49067 5.12691 3.38095 5.20068 3.28867 5.29361C3.1964 5.38653 3.12339 5.49678 3.07386 5.618C3.02432 5.73923 2.99923 5.86905 3.00002 6V7ZM3.00002 15H21V13H3.00002V15Z" fill="#0C66E4"/>
                                            </svg>
                                        </span>
                                    </button>
                                    <button class="action-button filter">
                                        <span>
                                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M10 3H4C3.44772 3 3 3.44772 3 4V10C3 10.5523 3.44772 11 4 11H10C10.5523 11 11 10.5523 11 10V4C11 3.44772 10.5523 3 10 3Z" fill="#44546F"/>
                                            <path d="M10 13H4C3.44772 13 3 13.4477 3 14V20C3 20.5523 3.44772 21 4 21H10C10.5523 21 11 20.5523 11 20V14C11 13.4477 10.5523 13 10 13Z" fill="#44546F"/>
                                            <path d="M20 3H14C13.4477 3 13 3.44772 13 4V10C13 10.5523 13.4477 11 14 11H20C20.5523 11 21 10.5523 21 10V4C21 3.44772 20.5523 3 20 3Z" fill="#44546F"/>
                                            <path d="M20 13H14C13.4477 13 13 13.4477 13 14V20C13 20.5523 13.4477 21 14 21H20C20.5523 21 21 20.5523 21 20V14C21 13.4477 20.5523 13 20 13Z" fill="#44546F"/>
                                            </svg>
                                        </span>
                                    </button>
                                </div>
                            </div>

                        </div>
                        <div class="table-wrapper">
                            <table>
                                <thead>
                                    <tr>
                                        <th>Order No</th>
                                        <th>Supplier's Name</th>
                                        <th>Type</th>
                                        <th>Date</th>
                                        <th>Total</th>
                                        <th>Quantity</th>
                                        <th>Quantity Returned</th>
                                        <th>Status</th>
                                        <th>Actions</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr v-for="(purchaseOrder, index) in purchaseOrders" :key="index">
                                        <td>{{ purchaseOrder.orderNumber }}</td>
                                        <td>{{ purchaseOrder.supplierName }}</td>
                                        <td>{{ purchaseOrder.type }}</td>
                                        <td>{{ purchaseOrder.date }}</td>
                                        <td>{{ purchaseOrder.total }}</td>
                                        <td>{{ purchaseOrder.quantity }}</td>
                                        <td>{{ purchaseOrder.quantityReturned }}</td>
                                        <td> <span>{{ purchaseOrder.status }}</span> </td>
                                        <td>
                                            <span>
                                                <svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M10.5 17.5C11.4205 17.5 12.1667 16.7538 12.1667 15.8333C12.1667 14.9129 11.4205 14.1667 10.5 14.1667C9.57957 14.1667 8.83337 14.9129 8.83337 15.8333C8.83337 16.7538 9.57957 17.5 10.5 17.5Z" fill="#44546F"/>
                                                <path d="M10.5 11.6667C11.4205 11.6667 12.1667 10.9205 12.1667 10C12.1667 9.07952 11.4205 8.33333 10.5 8.33333C9.57957 8.33333 8.83337 9.07952 8.83337 10C8.83337 10.9205 9.57957 11.6667 10.5 11.6667Z" fill="#44546F"/>
                                                <path d="M10.5 5.83333C11.4205 5.83333 12.1667 5.08714 12.1667 4.16667C12.1667 3.24619 11.4205 2.5 10.5 2.5C9.57957 2.5 8.83337 3.24619 8.83337 4.16667C8.83337 5.08714 9.57957 5.83333 10.5 5.83333Z" fill="#44546F"/>
                                                </svg>
                                            </span>
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>

                    </div> 
                </div> 
            </div>
        </div>
            
        
    </AuthenticatedLayout>

</template>


<style scoped>

.supplier-options {
    display: flex;
  padding: 10px 26px;
  border-bottom: 1px solid #091E4224;
  font-size: 12px;
  line-height: 16px;
  justify-content: space-between;
  
}

.supplier-options div, .supplier-options span {
    display: flex;
    align-items: center;
    color: #172B4D;
    font-weight: 600;
}

.action-button {
  /* padding: 10px 20px; */
  /* border: none; */
  border-radius: 4px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2px 10px;
  gap: 5px;
  border: none;
}

.action-button span {
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 500;
}

.edit {
    background-color: #0C66E4;
    color: white;
    margin-right: 1rem;
}

.edit span {
    color: white;
}

.supplier-container {
    background-color: #F7F8F9;
}

.supplier-details-container {
    padding: 10px 26px;
}

.supplier-info {
    display: flex; 
    gap: 2rem;
}

.contact h4 {
    color: #172B4D;
    font-weight: 600;
    font-size: 12px;
    line-height: 16px;
    margin-bottom: 0.8rem;
}

.address, .address div {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    color: #44546F;
    font-size: 12px;
    line-height: 16px;
    font-weight: 600;
}

.supplier-contact {
    display: flex;
    gap: 2rem;
}

.supplier-purchase-details-container {
    padding: 16px 0;
    display: flex;
}

.supplier-purchase-details {
    background-color: white;
    border: 1px solid #091E4224;
    padding: 20px 20px;
    border-radius: 8px;
    display: flex;
    gap: 30px;
}
 
.purchase {
    display: flex;
    flex-direction: column;
    padding-right: 30px;
    border-right: 1px solid #091E4224;
    gap: 1rem;
}

.purchase:last-child {
    border: none;
}

.purchase-order-number {
    display: flex;
    align-items: center;
    gap: 1.5rem;
}

.purchase-order {
    font-size: 12px;
    line-height: 16px;
    color: #626F86;
    font-weight: 500;
}

.purchase-number {
    padding: 2px 5px;
    background-color: #091E420F;
    border-radius: 4px;
    font-size: 10px;
    line-height: 12px;
    font-weight: 600;
    color: #172B4D;
}

.purchase-price {
    font-size: 12px;
    font-weight: 600;
    color: #172B4D;
    line-height: 16px;
}

.option {
    display: flex;
    gap: 20px;
    padding: 10px 26px;
}

.table-container {
    background-color: white;
    padding: 10px 26px;
}

.procurement-header-container {
  padding-bottom: 12px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.procurement-header {
  font-size: 12px;
  line-height: 16px;
  font-weight: 600;
  color: #172B4D;
}

.actions {
  display: flex;
  justify-content: flex-end;
  gap: 10px;
}

.action-button {
  /* padding: 10px 20px; */
  /* border: none; */
  border-radius: 4px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2px 10px;
  gap: 5px;
}

.action-button span {
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 500;
}

.action-button.filter {
  background-color: transparent;
  color: #172B4D;
  border: 2px solid #091E4224;
  font-weight: 500;
}

.filter span {
  font-weight: 550;
}

.action-button.download {
  background-color: #0C66E4;
  color: #ffffff;
  border: none;
  font-weight: 500;
}

.branch-container {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0.5rem 1rem;
    background-color: #091E420F;
    font-family: 600;
    gap: 10px;
    border-radius: 6px;
    font-size: 14px;
    margin-left: 35px;
}

.branch-container span {
    display: flex;
    align-items: center;
    color: #172B4D;
}

/* .table-wrapper {
    border: 1px solid #091E4224;
    border-radius: 10px;
    
} */

table {
    width: 100%;
    border-collapse: collapse;
    border: 1px solid #091E4224;
    border-radius: 10px;
}

th, td {
    color: #172B4D;
    font-size: 12px;
    line-height: 16px;
}

table thead tr:first-child {
    border-top-left-radius: 8px;
}

th {
    text-align: left;
    font-weight: 600;
    padding: 5px 6px;
    border-bottom: 1px solid #091E4224;
}

table td {
    border-bottom: 1px solid #091E4224;
    padding: 10px 6px;
    color: #44546F;
    font-weight: 500;
    
}

table thead tr {
    background-color: #F7F8F9;
    
}

table tbody tr:first-child {
    background-color: #091E4224;
}

table tr:last-child td {
    border-bottom: none;
}

table tbody tr td:nth-child(8) span  {
    display: flex;
  align-items: center;
  padding: 0.2rem 0.5rem;
  background-color: #BAF3DB;
  color: #216E4E;
  border-radius: 5px;
  font-weight: 700;
  width: fit-content;
}

</style>