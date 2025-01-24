<script setup>

</script>

<template>
<div>
    <div>
        <div >
            Dashboard
        <div>
            All Suppliers
        </div>
        <div>
            Purchase order 
        </div>   
        <div>
            Payments
        </div>
        <div>
            Supplier's return
        </div>
        <div>
            Product request
        </div>
    </div>
            <div class="actions">
                <button class="action-button filter">Filter</button>
                <button class="action-button download">Download Report</button>
                </div>
            <div>
            <h1 class="dashboard-header">PROCUREMENT DASHBOARD</h1>
        </div>
        <div>
            <div class="metric-card">
                <h2 class="metric-title">Received Suppliers</h2>
                <p class="metric-value">60</p>
                <p class="metric-subtext">12.95% Compared to last month</p>
            </div>

            <div class="metric-card">
                <h2 class="metric-title">Received Products City</h2>
                <p class="metric-value">20,550</p>
                <p class="metric-subtext">2.95% Compared to last month</p>
            </div>
           <div class="metric-card">
                <h2 class="metric-title">Value of Received Products</h2>
                <p class="metric-value">5,250,000</p>
                <p class="metric-subtext">-12.95% Compared to last month</p>
            </div>
            <div class="metric-card">
                <h2 class="metric-title">Orders Pending Arrival</h2>
                <p class="metric-value">15</p>
            </div>
            <div class="metric-card">
                <h2 class="metric-title">Orders Passed Delivery Date</h2>
                <p class="metric-value">10</p>
            </div>
            <div class="metric-card">
                <h2 class="metric-title">Average Processing Time</h2>
                <p class="metric-value">06 Days | 14 Hours | 53 Minutes</p>
            </div>
         </div>
        <div>
            <div class="section-card">
                <div>
                    <h2 class="section-title">Shelf Life Analysis</h2>
                    <p> Riddle of residential products with deeply blue fruit fill trenchess</p>
                </div>
                <div class="section-card">
                    <p>Less than 18 Months</p>
                    <p>More than 18 Months</p>
                </div>
            </div>

            <div class="section-card">
                <div>
                    <h2 class="section-title">Storage Space</h2>
                    <p>Riddle of used in free storage space</p>
                </div>
                <div class="section-card">
                    <p>Used space</p>
                    <p>Free Space</p>
               </div>
            </div>
        </div>
            <div class="section-card">
                <p>Less than 18 Months</p>
                <p>More than 18 Months</p>
            </div>
        </div>
        </div>
        <div>
            <div class="section-card">
            <h2 class="section-title">Top Suppliers</h2>
            <ul class="section-list">
                <li>Errors Pharmaceuticals</li>
                <li>Fiducal Healthcare</li>
                <li>Errors Pharmaceuticals</li>
                <li>Fiducal Healthcare</li>
            </ul>
            </div>

            <div class="section-card">
            <h2 class="section-title">Top Products</h2>
            <ul class="section-list">
                <li>Posecisional</li>
                <li>Reproton</li>
                <li>Amexicitis</li>
                <li>Vitamin C Tables</li>
                <li>Adenosine-Lumination</li>
            </ul>
        </div>
</div>
</template>

<style scoped>
.dashboard {
  padding: 20px;
  background-color: #f4f4f4;
  min-height: 100vh;
  font-family: Arial, sans-serif;
}

.dashboard-header {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}

/* Metrics Grid */
.metrics-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-bottom: 20px;
}

.metric-card {
  background-color: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.metric-title {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 10px;
}

.metric-value {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 5px;
}

.metric-subtext {
  font-size: 14px;
  color: #666;
}

.section-card {
  background-color: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  margin-bottom: 20px;
}

.section-title {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 10px;
}

.section-content {
  font-size: 16px;
  color: #333;
}

.section-list {
  list-style-type: disc;
  padding-left: 20px;
}

.section-list li {
  font-size: 16px;
  color: #333;
  margin-bottom: 5px;
}

.actions {
  display: flex;
  justify-content: flex-end;
  gap: 10px;
}

.action-button {
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.action-button.filter {
  background-color: #007bff;
  color: #ffffff;
}

.action-button.download {
  background-color: #28a745;
  color: #ffffff;
}

.action-button.filter:hover {
  background-color: #0056b3;
}

.action-button.download:hover {
  background-color: #218838;
}
</style>