## Step one: choose a data visualization from MakeoverMonday
I selected a specific visualization that portrays the market share of global electric vehicle sales on a quarterly basis from Q3 2021 to Q2 2023. My rationale for choosing this visualization is threefold. Firstly, it complies fully with the rubric requirements, as the underlying data is readily extractable and can be replicated with precision. Secondly, the dataset is both clear and succinct, obviating the need for any preliminary data cleaning or preprocessing — a factor that significantly streamlines the visualization process. Lastly, the subject of the dataset resonates with my personal interests in sustainability and decarbonization, with electric vehicles being a topic I am particularly passionate about.
![image](https://www.counterpointresearch.com/wp-content/uploads/2023/06/Global-EV-market-share-Q2-2023.png)
Source: [Global Passenger Electric Vehicle Model Sales Tracker: Q1 2018 – Q2 2023](https://www.counterpointresearch.com/research_portal/)

## Step two: critique the data visualization
What Doesn't Work As Well:
- The color palette could be improved. The red and pink hues used for Tesla and BYD Auto, respectively, are too similar and can cause confusion. This is particularly important as these companies' shares are often adjacent within the bars.
- The "Others" category, represented in grey, becomes less dominant over time but does not draw much attention due to its neutral color. This is a critical trend that might be overlooked due to its subdued presentation.

Potential Improvements:
- Introduce a wider range of colors with higher contrast to differentiate between companies more distinctly.
- Incorporate interactive elements that allow viewers to hover over segments to see more details, such as the actual number of units sold or year-over-year growth rates.
- Add trend lines or annotations to highlight significant changes, such as a major increase or decrease in a company's market share, to guide the viewer to these points of interest.
- I would consider a different visualization type, like a line chart, to depict the change over time more dynamically. Each company could have its line with points for each quarter, making it easier to follow individual trajectories.

## Step three: sketch out a solution
Informed by the insights from the critique methodology, I have endeavored to reimagine the visualization, the draft of which is presented below. I explored an alternative approach, opting for an area chart to represent the data. This choice was strategic; an area chart not only illustrates the evolution of market shares over time with greater dynamism but also clearly delineates each company's share per quarter. While I have not addressed the issue of the color palette in this preliminary draft, I plan to refine it in Tableau during Step five. The primary aim of this draft, and the subsequent interview, is to gauge the efficacy of the area chart in conveying the information. Specifically, I intend to determine if the area chart facilitates a more intuitive understanding for the audience compared to the bar chart or other chart types, such as the line chart.

![image](https://github.com/runzhes/94870/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20231113154346.jpg?raw=true)

## Step four: Test the solution
Question List:
- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

Participant 1 (Engineering Student, 25)
- Noted that Tesla leads in market share within the EV market, with BYD and Volkswagen also being significant players.
- Expressed confusion regarding the stacked area chart, questioning the representation of market shares as ranges and why Tesla appears to have a full 100% share.
- Suggested potential audience as prospective EV customers and environmentalists.
- Advocated for a line chart to depict market share trends over time, highlighting that stacked area charts may not show quarter-to-quarter changes effectively.
- Recommended that visualizations explicitly indicate stacked market shares and incorporate interactive labels for each data point.
- Emphasized that the choice of visualization should match the presenter's intent.

Participant 2 (Economics Student, 23)
- Understood the visualization to be about the global passenger EV market share.
- Recognized Tesla's market dominance and sought clarity on BYD Auto's market role.
- Questioned why all companies' market shares add up to 100%, finding the shaded areas of the chart unclear.
- Identified the intended audience as EV industry investors, company employees, and executives.
- Proposed reordering the stacked areas to highlight specific brands based on the target audience, using color differentiation.
- Suggested adding labels to emphasized data points and including the average market share level for each company within the timeframe.

In-Class Discussion
- A consensus was reached to remove the "Others" category to reduce distraction and improve focus on the top players.
- If the "Others" category is removed, the title should be changed to "Global Top 3 Passenger EV Company Market Share."
- Recommended against adding labels to every data point to avoid clutter, suggesting the addition of labels only to emphasized points.

## Step five: Build your solution
Reflection on Feedback:
- It's recognized that the stacked area plot might introduce confusion in visualizing market shares.
- The audience could include a diverse group ranging from consumers and environmentalists to investors and company staff.
- The careful curation of stacked areas in terms of selection, sequencing, and color is crucial for effectively communicating the intended message to the audience.
- Additional labels can serve to impart greater detail.
- Incorporating an average market share metric could serve as a useful reference point.
- The prominence of the "Others" category may divert attention from key data.

Proposed Design Modifications:
- Omit the "Others" category to sharpen the focus on the market shares of "Tesla," "BYD," and "Volkswagen."
- Revise the title to "Market Share Trends of Top 3 Global Passenger EV Companies (Q3 2021–Q2 2023)."
- Arrange the stacked areas in ascending order based on market share size.
- Allocate a distinct color to each EV manufacturer to facilitate clear differentiation.
- Label data points for the most recent quarter (Q2 2023) explicitly, with additional data being accessible interactively.
- Introduce a line to depict the average market share over the time period for benchmarking.
- Enhance the visualization with highlights on some of the leading EV brands for enriched context.

The modified design is shown below:
![image](https://github.com/runzhes/94870/blob/main/step%205.png?raw=true)

[Go back to main portfolio page](README.md)
