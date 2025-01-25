<script setup>

</script>

<template>
<div>
    <div>
        <div>
            back
        <div>
            SUPPLIER'S DASHBOARD
        </div>
            <button>Edit</button>
        </div>
    </div>
    <div>
        <h4>Supplier info</h4>
        <p>Fidson Healthcare</p>
        <p>4, Road 56, Lagos, Nigeria</p>
    </div>
    <div>
        <h4>Contact info</h4>
        <p>musa@example.com</p>
        <p>+234 801 234 5678</p>
    </div>
    <div>
        <h4>Bank info</h4>
        <p>Fisrt Bank Plc</p>
        <p>-----</p>
    </div>
    <section>
        <div>
            <p>Purchase Order</p> <div> 40 </div>
            <p>5,250,000</p>
        </div>
        <div>
            <p>Invoices</p> <div> 20 </div>
            <p>5,250,000</p>
        </div>
        <div>
            <p>Payments</p> <div> 25 </div>
            <p>5,250,000</p>
        </div>
        <div>
            <p>Purchase Qty</p> 
            <p>12</p>
        </div>
        <div>
            <p>Returns</p>
            <p>0</p>
        </div>
    </section>
    <div>
        <p>Purchase order</p>
        <div>Page 1/6</div>
        <div class="search-container">
            <input type="text" class="search-input" placeholder="Search">
        </div>
    </div>
    <div>
        Invoices
    </div>
    <div>
        Payment
    </div>
</div>
<table>
    <thead>
        <tr>
            <th>Order No</th>
            <th>Supplier's Name</th>
            <th>Type</th>
            <th>Date</th>
            <th>Total</th>
            <th>Quantity</th>
            <th>Quantity Returned</th>\
            <th>Status</th>
            <th>Actions</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Daniel</td>
            <td>Abiodun</td>
            <td>Ariyo</td>
            <td>Dayo</td>
            <td>Ibidapo</td>
            <td>favour</td>
            <td>Ridwan</td>
            <td>Tobi</td>
            <td>Titi</td>
        </tr>
    </tbody>
</table>
</template>

<style scoped>
table {
            width: 100%;
            border-collapse: collapse; /* Ensures borders are merged */
        }
        th, td {
            border: 2px solid #000; /* Adds a solid black border to cells */
            padding: 10px; /* Adds padding inside cells */
            text-align: left; /* Aligns text to the left */
        }
        th {
            background-color: #f2f2f2; /* Adds a light gray background to header cells */
        }

        .search-container {
            display: flex;
            justify-content: center;
            margin: 20px;
        }

        .search-input {
            padding: 10px;
            width: 100px;
            border: 2px solid #ccc;
            border-radius: 5px 0 0 5px;
            outline: none;
            font-size: 16px;
        }
</style>