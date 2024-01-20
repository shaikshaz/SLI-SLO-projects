# SLI-SLO-projects
SITUATION: There is a E-commers web application called “Shop fast” which is getting a huge incoming traffic and we must reduce the issue faced during these situations like latency, downtime of application, Browsing and checkout issues.

TASK: Task is to develop a set of Service Level Indicators (SLIs) and Service Level Objectives (SLOs) for this application. Shop Fast's primary functionalities include product search, user account management, product browsing, shopping cart management, and the checkout process so that users can experience high quality experience and system reliability.

ACTION: Developing Service Level Indicators (SLIs) and Service Level Objectives (SLOs) is crucial for measuring and maintaining the reliability of your application. These SLIs and SLOs provide a foundation for monitoring and ensuring the reliability of Shop Fast’s key functionalities. Adjustments may be needed based on specific business goals and user expectations.
Here is a starting format for creating SLIs and SLOs for the Shop fast webapplication:
Product Search Functionality:
SLI:
•	Metric: Percentage of successful product searches.
•	Formula: (Successful Searches / Total Searches) * 100 => (990/1000) *100
SLO:
•	Target: Achieve a 99.9% success rate for product searches.
Rationale:
•	A high success rate (99.9%) in product searches ensures users can quickly find the products they are looking for, enhancing user satisfaction and engagement.
________________________________________
User Account Management:
SLI:
•	Metric: Percentage of successful user account actions (login, registration, password reset).
•	Formula: (Successful Actions / Total Actions) * 100=> (980/1000) * 100
SLO:
•	Target: Maintain a 99.8% success rate for user account actions.
Rationale:
•	Reliable user account actions contribute to a seamless user experience, preventing frustration and improving user trust in the platform.
________________________________________
Product Browsing:
SLI:
•	Metric: Average response time for product browsing.
•	Formula: Sum of Response Times / Total Browsing Requests= > (185/1000) *100
SLO:
•	Target: Keep the response time under 200 milliseconds for 95% of product browsing requests.
Rationale:
•	Fast response times (under 200 milliseconds) in product browsing enhance user experience, encouraging users to explore and view more products.
________________________________________
Shopping Cart Management:
SLI:
•	Metric: Percentage of successful shopping cart updates.
•	Formula: (Successful Updates / Total Updates) * 100=> (997/1000) *100
SLO:
•	Target: Achieve a 99.7% success rate for shopping cart updates.
Rationale:
•	Accurate and reliable shopping cart updates are critical to providing users with a smooth and frustration-free shopping experience.
________________________________________
Checkout Process:
SLI:
•	Metric: Percentage of successful checkouts.
•	Formula: (Successful Checkouts / Total Checkouts) * 100 => (995/1000) *100
SLO:
•	Target: Maintain a 99.5% success rate for the checkout process.
Rationale:
•	A high success rate (99.5%) in the checkout process is crucial for completing transactions and ensuring user satisfaction.
2. Error Budget Calculation
•	Error Budget is calculated as 100% - SLO Target.
Product Search Functionality:
•	Error Budget = 0.1% (Success is 99%)
User Account Management:
•	Error Budget = 0.2% (Success is 99%)
Product Browsing:
•	Error Budget = 5% (Success is 95%)
Shopping Cart Management:
•	Error Budget = 0.3% (Success is 99%)
Checkout Process:
•	Error Budget = 0.5% (Success is 99.5%)
RESULT:  As seen in the metrics the overall performance of the website is increased by monitoring with SLI’s and whereas SLO’s helps to set targets and reach them improving overall efficiency by 99%.
These specific SLIs and SLOs, along with error budgets, provide a measurable and achievable framework to ensure a high-quality user experience and system reliability for Shop Fast. Regular monitoring and adjustments will be crucial to achieving and maintaining these service levels.
