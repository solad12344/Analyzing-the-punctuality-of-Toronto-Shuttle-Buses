# Analyzing-the-punctuality-of-Toronto-Shuttle-Buses
 This project focused on  improving the punctuality in the Toronto Transit System by analyzing data, creating visualizations, and developing a delay reduction simulation model.

Data Source: https://open.toronto.ca/dataset/ttc-bus-delay-data/

Living in Toronto, the journey to school was more of an adventure than it should have been. No matter how early I woke up or how quickly I got ready, the shuttle bus — the one crucial link between my home and school — was frustratingly unreliable. It seemed almost indifferent to the time of day or the weather conditions. Whether the sun was shining brightly, snow was blanketing the streets, rain was pouring down, or the sky was crystal clear, that bus had a talent for never arriving on schedule.

I found myself spending countless mornings and afternoons standing at the bus stop, waiting. Sometimes I’d try to guess the reason behind today’s delay, other times I’d just sigh and resign myself to another late arrival. It became a routine part of my day, this odd blend of hope and resignation, always wondering but never really understanding why punctuality was such an elusive concept for this shuttle service.

Now, I’m turning my frustration and curiosity into action. This project isn’t just about venting; it’s about uncovering the truth behind the chronic lateness of these buses. I’m on a mission to dig deep, to peel back the layers of scheduling mishaps, traffic patterns, or any other factors that might explain this consistent tardiness. Ultimately, I hope to find solutions that could make public transportation more reliable for everyone who, like me, has ever found themselves endlessly waiting for a bus that seems to operate on its own mysterious schedule.

Hence, The objectives for this project are:

1. Understanding the Patterns of Delays.
2. Quantifying the Impact by Total Number of Incident and Total Delay.
3. Identifying Key Problem Areas.
4. Time-of-Day Analysis for various categories affecting the delay time.
5. Simulating Improvement Scenarios.
6. Recommendations

Based on the Objectives, I came up with several visual that will help me get the answers I need.

Counting the Cost of Delays: The Hidden Price of Public Transit

![image](https://github.com/user-attachments/assets/01aec877-c9ed-4615-9f9e-30b2c760c127)


Dashboard 1 Depicting how much time you lost waiting for delayed buses
This visual, a part of my project’s data analysis tool, allowed users to select a route, time of day, and whether it was a weekday or weekend. It then calculated the total time lost due to delays. Seeing the hard numbers in front of me transformed my personal annoyance into a concrete problem, one that was not just mine but shared by countless others who depended on route 11 to navigate their daily lives.

There it was, quantified and impossible to ignore. If I’d taken route 11 every afternoon on a weekday for the past five years, I’d have lost 7,827 minutes. That’s over 130 hours — a staggering amount of time that could have been invested in studying, working, or simply enjoying life. Time is indeed money, and according to this eye-opening revelation, I had been unwittingly spending it without any returns.

This discovery fueled my determination to delve deeper. It wasn’t just about my own losses anymore. It was about a systemic failure that affected a community of commuters. The numbers on the screen became more than just a personal grievance; they were a call to action. I was ready to challenge the status quo, armed with data and a newfound resolve to advocate for change. The next step was to present these findings to those who had the power to make a difference. It was time to turn the tide on time lost and make every minute count.

Decoding TTC Delays: Understanding the Odds of a Late Bus Ride
![image](https://github.com/user-attachments/assets/136d1d34-b5ae-47ac-95ea-0eb31e6dd0cb)

Dashboard 2 shows the Bus Delay causes
The next visual in my analysis was just as startling, laying bare the intricate web of reasons behind the delays. It was a detailed pie chart of probabilities, a gamble every commuter unknowingly took when they stepped onto a TTC bus.

The numbers were clear: a 31% chance that any delay could be attributed to a mechanical issue. It begged the question — was there a lack of regular maintenance? A deeper issue of misallocated resources, perhaps? It seemed like a significant portion of the delays could be mitigated with better upkeep, which, of course, circled back to how tax money was being spent.

Operational issues accounted for 14% of delays, hinting at potential inefficiencies within the system’s management. Another 10% were due to buses going off-route, an alarming statistic that raised concerns about planning and oversight. General delays and investigations rounded out the chart, with 9% and 7% respectively, while cleaning issues were the least likely cause at 6%.

These figures painted a picture of tax money not just being spent, but wasted — not on the maintenance and efficiency that could streamline the system, but on the consequences of neglect. It was a fiscal leak, dripping steadily from the city’s coffers, and it was costing us all — not just in time, but in the quality of the services that our taxes were supposed to ensure.

The chart became another piece of the puzzle in my project, a visual representation of a problem that was more than just personal. It was a systemic failure that echoed in the empty promises of bus schedules and the sighs of stranded passengers. With this data, I aimed to raise awareness, to bring to light the need for reform, for accountability, and for the responsible use of the funds that we, as citizens, contributed to keep the city moving. The journey for answers had become a crusade for change, one pie chart at a time.

Analyzing the Ebb and Flow of Transit Delays: A Yearly TTC Synopsis
![image](https://github.com/user-attachments/assets/c4418fca-f808-452f-93cc-94fba701cf2e)

Dashboard 3 shows the Yearly Delay Analysis of TTC Bus
The next set of visuals presented a clear, data-driven picture of TTC delays. The bar graph showed fluctuations in delays year over year, with a significant spike in 2019 that warranted a closer look. To the side, pie charts dissected these delays by their causes, revealing that mechanical and general delays were the most significant contributors to the problem.

Below, the donut charts measured the sum and average duration of delays by incident type. Here, it became clear that diversions and mechanical issues were not just frequent but also caused the longest waits.

This information was crucial. It wasn’t just the inconvenience of waiting that was at stake — it was the broader implication of time lost across the population, aggregated over years. The consistent mechanical issues pointed towards a potential shortfall in maintenance and investment in the city’s bus fleet.

By integrating these findings into my project, I began to see the scope of change needed in the TTC system. It was apparent that taxpayer money wasn’t being optimized, leading to repeated service disruptions. This data could be pivotal in advocating for a strategic review and reallocation of funds to address the root causes of these delays, ensuring more reliable service for Toronto’s commuters.

Timing and Location of Transit Delays: A Closer Look at TTC’s Trouble Spots
![image](https://github.com/user-attachments/assets/07d4a393-e7fc-4e1c-9851-ae31aa87061c)

Dashboard 4 shows the Delays and their location
This visual focused on the timing and locations where the TTC faced the most delays. The title at the top, “Which Incidents causes the most delay, When does it happen and Where?” set the stage for a deep dive into the specifics of the transit system’s weak points.

Mechanical issues clearly led the list of incidents, with a staggering count that dwarfed other causes. It was a visual confirmation of the earlier data, emphasizing just how much these technical failures impacted the overall system. The chart also detailed the frequency of other types of delays like operational issues and general delays, each adding to the complex tapestry of problems.

On the right, a treemap showed the locations with the highest counts of incidents. Kennedy Station stood out, a hotspot for delays, with other stations like Kipling and Eglinton following. It was an intriguing spread that suggested certain areas might be more prone to issues, or perhaps they were simply busier hubs with amplified effects from any disruption.

The time-of-day bar at the bottom (where users can choose the time of day to figure out when delays were most happening) indicated that the noon and night hours were particularly problematic. This was an essential piece of the puzzle; not only did it highlight when the delays were happening, but it also suggested when maintenance and operational efforts should be most intensely focused.

Bringing this visual into my growing project, I saw a narrative forming — a story of a transit system with identifiable patterns of disruption. This chart wasn’t just another set of statistics; it was a roadmap for where and when to concentrate improvements.

Strategic Impact Assessment: Reducing TTC Delays Through Targeted Actions
![image](https://github.com/user-attachments/assets/4b4d0080-55ef-4e0b-9892-01b4e0f089c5)

Dashboard 5 is the Delay Simulation
The final piece of the puzzle in my investigation was a dynamic ‘Delay Simulation’ tool. The tool’s interface was straightforward, yet the data it crunched in the background was anything but simple. It displayed a stark figure: 195.96K incidents had led to a total of 402K minutes of delay.

But it was the simulation functionality that truly caught my attention. It showed that reducing the number of incidents by just 7K could potentially cut the total delay time by a whopping 100.55K minutes. This was the kind of actionable data that could make a real difference. It wasn’t about pointing fingers; it was about finding levers to pull that could improve the efficiency of the entire transit system.

This simulation became a critical element of my project, a tool to model how even small improvements in certain areas could have a disproportionate impact on the system’s overall performance. It underscored that a targeted approach, focusing on high-incident locations or times, could substantially reduce delays.

I began to imagine the possibilities: what if maintenance crews could be better allocated? What if we could predict and prevent certain types of incidents? This wasn’t just about improving a bus schedule; it was about reimagining how the city approached public transit problems.

As I prepared to share my findings, this Delay Simulation would serve as a centerpiece, a clear demonstration that with the right focus and resources, the TTC could not only save time for its riders but also use taxpayer money more effectively. This was about building a case for smarter investment in public services — a case backed by solid data and a clear vision for a more efficient future.

Conclusion and Recommendation
As I reached the conclusion of my project, the aggregated data coalesced into a clear picture. I had identified the most pressing issues causing delays within the TTC: mechanical failures and operational inefficiencies stood out as the leading culprits. My research also pinpointed the locations where commuters experienced the most significant holdups, with Eglinton Station being a notable example.

My Recommendations are very straightforward:

Enhanced Maintenance: Address mechanical issues as a top priority through increased funding for maintenance and more rigorous inspection schedules.
Operational Overhaul: Review and optimize operational procedures to prevent buses from being utilized off-route, thereby minimizing delays.
Incident Management: Improve training for dealing with collisions and emergencies and streamline the investigation process to reduce delay times.
Focus on Hotspots: Allocate more resources to delay hotspots like Eglinton Station, implementing targeted solutions such as additional staff or improved infrastructure.
Data-Driven Scheduling: Utilize delay data to adjust bus schedules and ensure better reliability, especially during peak hours and at high-incident locations.
With the report complete, it is time to present these findings. The aim was not just to highlight the flaws but to offer a way forward, a strategy that could be implemented for tangible improvements. This was about taking the myriad strands of data and weaving them into a cohesive plan of action, one that could lead to a more efficient and reliable transit service for the city of Toronto. It was time for the data to make the journey from charts and graphs to real-world change.

Reference:

Open data dataset. City of Toronto Open Data Portal. (n.d.). https://open.toronto.ca/dataset/ttc-bus-delay-data/
