# Resume Update Questionnaire

Answering these questions will help us gather the details needed to update your resume with your latest skills and accomplishments. Please be as specific as possible, and think about results and impact.

### Current Role: Application Developer II at Los Angeles Dodgers, December 2021 - Current.

1.  **Major Projects & Accomplishments:** Since your last resume update, what are the 2-3 most significant projects you've worked on? What was your specific role and contribution?
    *   *People Operations Employee Scorecard: "I was the lead developer on the new Employee Scorecard, employee self-review. The employee fills out answers to a template of questions based on their role, and once it is done, it goes to the supervisor for reivew. The supervisor will review the employees self review, leave their own, and give a score. Then it is handed off to the people operations department. They will either approve the supervisor review, or request the supervisor to make specific changes. After final approval, the supervisor can release the review, with limited visibilty back to the employee. This project safely uses several roles to ensure data security and is used by all front office employees (around 500). The origanization used to pay for Lattice and I was able to build a replacement in house."*
    *   *Family Programs: "To give our team an edge, we built a secure webapp for the wives of the players to have critical information about travel arrangements, important contacts, scheduling, and important documents. I have an NDA about the details of this project so I cannot dislose more details, however I feel our product is better than what other teams are also doing.
    *   *People Operations Emergency and Critical Alerts: A new webapp tool for the People Operations department. It is a broadcast form in which different filters of employees can be applied. SMS/MMS and or Emails can be sent from this platform. We used Twilio for SMS and Microsoft GraphApi to send emails. This was extremely important when the stadium was locked down due to nearby protests, and was heavily used when the front office travled to Toronto. The People Operations department was able to send fast alerts to all the travelers about bus schedule departures, plane arrivals and departures, and hotel information for each travel group.

2.  **Technical Contributions:** What new technologies, languages, frameworks, or tools have you started using? Have you become a subject matter expert in any particular area?
    *   *Google Cloud Platform: Cloud Build, Cloud Run, IAM roles, Cloud Storagem BigQuery, Cloud SQL, Cloud Scheduler, VPC Network, Load Balancer, Secrets Manager, Redis Cache, ETL.
    *   *Programming Languages: Dotnet c#, React TS, Python. 

3.  **Quantifiable Impact:** Can you quantify the impact of your work? Think in terms of numbers, percentages, or time saved.
    *   *Did you improve performance? Surprisingly, there were about a dozen different departments that did most of their work in excel. About half od my work was to build them a form on our Intranet site so they could have all their information in a single location and have email alerts. This reduced errors, ensured that forms did not go missing, and sped up the approval process by simply clicking a button rather than having dozens of email chains.
    *   *Did you increase efficiency? (e.g., "Automated a manual process, saving the team 10 hours per week.")*
    *   *Did you reduce errors or bugs? In the app dev team, some daily processes were done using raw SQL queries. By creating an offical web page for this, and assigning proper user group permissions, we were able to delegate this work into other team who were responsible for this data. This was the case for making configuration changes to the intranet site, adding employees into the ticketing system, and adhering to data privacy laws for customer data.

4.  **Leadership & Mentorship:** Have you taken on any leadership responsibilities? *We have had two Fellow on our App Dev team, each stayed for 5 months. It was my job to make sure they were brought up to speed quickly so they can contribute faster. I was able to build out documentation for all of our projects, and build an app dev best practices document. By doing this and reviewing this with the Fellows early on, they were able to grasp company projects much sooner and contribute to code changes much quicker. I was also a mentor to a group of 6 fellows. We had monthly check ins to casually talk about projects and how they were adapting to life at the Dodgers. This was extremely valuable as it taught me to be a better listener.

5.  **Problem Solving:** Describe a particularly challenging technical problem you solved. What was the problem, what was your approach, and what was the outcome?
*   *Optimizing SMS throuput with Twilio. When we started using Twilio, we were using a local number that could only send 1 message per second. It was my job to figure out how we can speed up this process while keeping the cost to a minimum. I worked with the Twilio Sales Reps to explore all the different options they offered and at which rates. Once my suggestion was approved by Finance, I had to build a new tool on our Intranet so that employees can opt in and out of SMS messaging. At this point, we were able to fill out an application for a faster line. Once approved, I started experimenting with the new number. At first, long messages were broken up into different messages and receieve out of order for the user. After some research I found out this is a carrier specific problem. I also found out each message was using around 27 segments (each segment was a charge). I was able to build a conversion function that changed the text encoding to use the minimal amount of segments. After closely watching the way the tool was actually being used, I discovered that simply forcing an MMS by attaching a photo reduced the cost, turned each message into a single segment, and ultimately improved the throughput by 20x. Sometimes the toughest challenges are a blend of business and technical issues and requirements.

### Career Goals & Professional Summary

6.  **Next Career Step:** What kind of role are you targeting now? (e.g., Senior Software Engineer, Tech Lead, a specific domain like FinTech or cloud computing).

7.  **Key Strengths:** What do you now consider your top 3 professional strengths as a software engineer?
    *   *Example: "Building scalable APIs, optimizing database performance, and mentoring junior developers."*

### Skills & Continuous Learning

8.  **New Technical Skills:** Are there any new languages, frameworks, databases, or cloud technologies we should add to your "Technical Skills" section?

9.  **Personal Projects & Learning:** Have you worked on any personal coding projects, contributed to open-source, or completed any new certifications or courses since your last update?

Once you have some answers, we can start weaving this new information into your resume to make it shine.
