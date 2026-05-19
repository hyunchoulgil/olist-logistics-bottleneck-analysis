<div align="center">
  <img width="320px" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778136693/Logo-Olist_xeh1up.png" />
</div>
<h1 align="center">Regional Logistics Bottleneck Analysis in Brazil</h1>
<table align="center">
<tr>
    <td width="1440">
       <h2 align="center">Background</h2>
       <body>
      Following the previous <a href="https://github.com/hyunchoulgil/RFM-Customer_Analysis-">RFM customer analysis</a>, we identified that longer delivery days were associated with lower review scores. The <strong>Master–Platinum segments</strong>, which have strong potential for higher-value conversion, showed relatively long delivery times and lower satisfaction levels.

To improve customer satisfaction and support upselling into higher-value segments, reducing delivery lead time became a key priority. This follow-up analysis therefore investigates regional delivery delays in Brazil to identify logistics bottlenecks affecting customer experience. <br>
         <br>
</table>
<table align="center">
  <tr>
    <div width="920">
      <h1 align="center">Business Value</h1>
      <h2 align="center">Key Business Impact</h2>
  
- **Identifies Regional Delivery Bottlenecks**  
  Analyzes delivery performance by customer region, seller region, and shipping route to identify where logistics delays are concentrated.

- **Improves Customer Satisfaction**  
  Since longer delivery days are associated with lower review scores, identifying delay-prone regions helps prioritize improvements that can directly enhance customer experience.

- **Supports High-Value Customer Retention**  
  The previous RFM analysis showed that key customer segments had longer delivery times and lower satisfaction. This analysis helps uncover the regional causes behind those delivery issues.

- **Prioritizes Logistics Optimization**  
  By comparing delivery days and delay patterns across regions, the company can focus operational resources on the routes and states with the highest delivery risk.

- **Enables Data-Driven Decision Making**  
  The analysis provides actionable insights for data, logistics, and operations teams by connecting customer satisfaction issues with regional delivery performance.

  </table>
<h1 align="center">State-Level Delivery Pattern Analysis</h1>
<h2 align="center">Delivery Time Boxplot by Customer State</h2>
<img width="1000" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778825939/Boxplot_kgirvi.png" />
      </div>
      <td width="460" valign="top">
        <ol>
          <strong>1. Clear Regional Gap in Average Delivery Time</strong>
            <ul>
                <li>From left to right on the x-axis, the position of the boxes gradually shifts upward, showing a clear increase in median delivery time.</li>
              <li>South and southeastern states(SP, MG, PR), show relatively fast delivery performance, with median delivery times around 10 days. In contrast, more remote northern and northeastern states(AL, AP, AM) show much longer median delivery times, often exceeding 25 to 30 days. This indicates that the customer's delivery experience varies significantly depending on the state thet live in.</li>
            </ul>
          </li>
        </ol>
        </td>
      <td width="460" valign="top">
        <ol start="2">
            <strong>2. Extreme Delivery Delay Outliers in Major States (SP,MG,RJ)</strong>
            <ul>
              <li>A large number of outliers are concentrated above the boxes, especially in major states(SP, MG, RJ)</li>
              <li>Although these regions have short average delivery times, their sheer volume of orders leads to frequent extreme delays of 100 to 200+ days, triggered by events like logistics bottlenecks, strikes, or lost packages.</li>
            </ul>
            </li>
        </ol>
        </td>
      <td width="460" valign="top">
        <ol start="2">
            <strong>3. Higher Delivery Uncertainty in Remote Regions</strong>
            <ul>
              <li>As we move toward the right side of the chart, both the height of the boxes and the length of the whiskers increase.</li>
              <li>States such as PA, AL, AP, AM, and RR not only have slower deliveries but also show higher variability. This means delivery times are less predictable, making it harder to provide reliable estimates for customers in these regions.</li>
            </ul>
          </li>
        </ol>
      </td>
    </div>
<table align="center">
  <tr>
    <h2 align="center">Seller & Customer & Order Distribution</h2>
    <table align="center">
      <tr align="center">
    <td width="1000">
      <h3>Seller Map</h3>
    <img width="300" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778830472/seller_jmlppb.png">
    </td>
    <td width="1000">
      <h3>Customer Map</h3>
      <img width="300" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778830480/customer_wnqwnv.png">
    </td>
    <td width="1000">
      <h3>Order Map</h3>
      <img width="300" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778830486/order_ppyhih.png">
    </td>
  </tr>
  </table>
  </td>
  </tr>
</table>
<div align="center">
         <table>
  <tr>
    <td>
      <h3 align="left">Seller</h3>
      <ol>
        <strong>Strong concentration of sellers in the Southeast<ul></strong>
            <li>Green dots are heavily clustered around the southeastern coastal region, especially near São Paulo (SP) and Rio de Janeiro (RJ), while northern and inland regions have very few sellers.</li>
            <li>Olist supply network is highly concentrated in a few major metropolitan areas.</li>
          </ul>
        </li>
        </ol>
      <h3 align="left">Customer</h3>
      <ol>
        <li> One-Time Purchase Dominance – Limited Repeat Purchase Behavior <ul>
            <li>
              Compared to the seller map, the blue dots are spread much more widely across Brazil, especially along the northeastern coast and major inland cities.
            </li>
            <li>This shows a clear mismatch between supply concentrated in the Southeast and demand spread nationwide, leading to structurally longer delivery distances and delivery times</li>
          </ul>
        </li>
        </li>
        </ul>
      </ol>
      <h3 align="left">Order</h3>
      <ol>
        <strong>Spending Concentration in Mid-to-High Value Segments <ul></strong>
            <li>
              Most customers are concentrated in relatively lower spending ranges, while a small number of customers show exceptionally high spending amounts.
            </li>
            <li>This indicates a long-tail spending structure, where a limited group of high-value customers contributes disproportionately to revenue.</li>
            <li>Monetary Score 1 accounts for just 1% of customers, while Scores 2 and 3 account for 3% and 7%, respectively. In contrast, a larger share of customers is concentrated in lower-value segments, especially Scores 6 to 9.</li>
        </ul>
        </ol>
      </table>
</div>
      <table align="center">
  <tr>
    <h2 align="center">High Delay States in Brazil</h2>
    <td width="1000">
    <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778827234/Delivery_Time_Distribution_by_Customer_State_v7oxx3.png">
    </td>
    <td width="1000">
      <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1778829755/delay_order_map_gs95xg.png">
      </li>
        </ul>
</td>
  <tr>
      <td width="500" valign="top">
      <h3 align="center">Delivery Lead Time Histogram by States</h3>
      <ul>
        <li>The analysis reveals high logistical efficiency in major southeastern metro areas like SP and RJ, with most regions maintaining an optimized delivery lead time of around 10 days on average.</li>
        <li>Conversely, Rio de Janeiro (RJ) shows a sharp peak around 10 days but displays a unique long-tail pattern stretching up to 60 days. This anomalous volatility has been identified as a priority for a follow-up deep-dive analysis.</li>
  <td width="500" valign="top">
      <h3 align="center">Highest Delivery Lead Time States in Brazil</h3>
      <ul>
        <li>Mapped the average delivery delays by state, revealing significant logistical bottlenecks concentrated in the northern and outlying northeastern regions.</li>
        <li>Due to infrastructural limitations and vast distances, the regions surrounding the Amazon basin are expected to face chronically entrenched delivery delays.</li>
        <li>To enhance delivery efficiency, strategic initiatives such as establishing a regional fulfillment hub or optimizing the last-mile delivery process in the Northeast are highly recommended.</li>
      </ul>
      </td>
  </table>
  </tr>
</table>
<table align="center">
  <h1 align="center">Deep Dive: Rio de Janeiro(RJ) Drilldown</h1>
  <h2 align="center">Delay Rate(%) by State</h2>
  <table align="center">
</table>
<img width="1000" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779093654/delay_rate_fwtrks.png" />
      </div>
      <td width="460" valign="top">
        <ol>
    </td>
    <td valign="top" width="500">
      <ul>
        <table>
      <tr>
        <td>
          <ul>
        <li>Validating the volatility seen in the distribution data, RJ ranks 4th in Brazil with a 12.1% delivery delay ratio, showcasing a severe gap between average speed and actual reliability.</li>
        <li>Despite both being high-volume metropolitan hubs, SP stabilizes at a 4.5% delay ratio, whereas RJ spikes at 12.1% (a 2.7x increase).</li>
        <li>This disparity indicates that RJ's supply chain bottleneck is not just a factor of city size, but is driven by unique regional challenges in the last-mile phase.</li>
        <li>
          Excluding the remote northeastern states with inherently long average lead times, this represents the 2nd highest delay rate in the entire country, making RJ the worst-performing major metropolitan area.</li>
      </ul>
    </td>
   </tr>
  </table>
<table align="center">
  <tr>
    <h2 align="center">RJ Delivery Delay Rate by Seller State</h2>
    <table align="center">
    <tr align="center">
      <td width="1000">
      <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779093450/c26a8a58-7425-405d-bb24-3dc35848b1c1_sw8a5f.png">
    <td width="1000">
      <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779127121/wef_kqqoct.png">
    </td>
      </table>
    <table>
      <tr>
        <td>
          <ul>
            <li>Rio de Janeiro (RJ) exhibits the highest logistics-driven delay share among all major states, with 78.5% of late orders caused purely by logistics and carrier inefficiencies.(1306/1664)</li>
            <li>Non-loyalty members have not sustained sales revenue and AOV growth beyond the pandemic boom, with sales revenue decreasing from $3.4M in 2019 to $2.2M in 2022, along with an AOV decline of 8% during the same period.</li>
            <li>In 2022, loyalty members spent almost $31 more on average than non-loyalty members ($245 vs. $214). AOV for loyalty members has steadily increased year over year, climbing 1.1% from 2021, while non-loyalty members' AOV declined by 18.7%.</li>
          </ul>
        </td>
  </tr>
      </table>
<table align="center">
    <tr align="center">
      <td width="450" valign="top">
      <h2>Top 5 States by Delivery Delay Volume</h2>
      <img width="450" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779083930/939e679d-e434-4935-8d84-f6766cc0cfeb_luwf7c.png">
        <h4>
        <strong>Top-selling categories(cama_mesa_banho and informatica_acessorios etc) attract the most customers, but some still experience long delivery times, making category-level delivery optimization essential for improving customer satisfaction.</strong>
      </h4>
    </td>
    </tr>
  </table>
<table align="center">
  <tr>
    <h2 align="center">Why is Rio de Janeiro (RJ) Experiencing High Delivery Delays?</h2>
    <table align="center">
    <tr align="center">
      <td width="1000">
      <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779090540/578d2649-ab11-4f03-a043-22d83f1be4c6_ubbq56.png">
    </td>
    <td width="1000">
      <img width="500" src="https://res.cloudinary.com/dysnnptit/image/upload/q_auto/f_auto/v1779094263/a2a07296-09b7-442d-ad5c-11bf525d020b_k7gm2n.png">
    </td>
  </tr>
</table>
    <table>
      <tr>
        <td>
          <ul>
            <li>Inbound logistics to RJ are heavily bottlenecked by inter-state routes, with São Paulo (SP $\rightarrow$ RJ, 15.5%) and Paraná (PR $\rightarrow$ RJ, 14.0%) ranking as the #1 and #2 highest delay sources.</li>
            <li>This proves that the root cause of the breakdown is not RJ's local network—which remains highly stable at a 6.5% delay rate—but rather the bottlenecks occurring along the long-haul line-haul corridors inbound from São Paulo (SP) and Paraná (PR).</li>
            <li>Focus on diversifying truck transit routes for the SP/PR $\rightarrow$ RJ corridors, while establishing border cross-docking centers to split and unload inbound freight before it clusters.</li>
          </ul>
        </td>
      </tr>
      </table>
<table align="center">
    <h1 align="center">Recommendations</h1>
    <h4 align="center">Based on the uncovered insights, here are actionable items by team that Olist can take away from our analysis.</h4>
      <ul>
         
         
