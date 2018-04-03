**NBA Player Shooting Visualization**


**DEMO**:


http://192.144.132.138:3000/




This is a web app that visualizes NBA player&#39;s shooting performance.

- Built a web app to visualize NBA player&#39;s shot performance using **React** , the open source **d3** -shotchart package and front-end development tools ( **Babel** , **NPM** , etc)
- Introduced a field goal percentage filter that controls the visualization to be the specified number of shots made
- Utilized react component library ( **Ant Design** ) to enhance component features

**Details of development**

- Created a dashboard to visualize individual player&#39;s shot data, including a shot chart and 4 line/bar charts.
- Implemented linked highlighting among all charts using raised common React state among charts.
- Created a field goal percentage filter to provide more detailed visualization areas with made shots.
- Developed a match filter to more specifically visualize stats for home, away, won and lost matches.

**Tech details**

- Designed a component hierarchy based on React framework, including a search bar and a dashboard to display individual player&#39;s info and visualize his shot performance

- Used an open source NPM package to build the shot chart to visualize player&#39;s shot performance in React

- Use React state to control the components. For example, use playerID to control which player&#39;s info and shot performance to be displayed

- Introduced two filters to control the visualization.

**Data Source**

The NBA&#39;s Stats API provides data for every single shot attempted during an NBA game since 1996, including location coordinates on the court. [**http://stats.nba.com**](http://stats.nba.com/)

**Shot Chart**

Shooting charts help you identify trends, strengths, weaknesses, and ultimately give you insights to improve your team&#39;s overall shooting percentage.

[**https://www.poundingtherock.com/2016/2/29/11135958/spurs-hire-leading-analytic-expert-goldsberry**](https://www.poundingtherock.com/2016/2/29/11135958/spurs-hire-leading-analytic-expert-goldsberry)
 

![1](https://user-images.githubusercontent.com/6482545/37437692-10981ce6-27c5-11e8-8fc8-04756841fdf8.jpg)
![2](https://user-images.githubusercontent.com/6482545/37437693-10adbf9c-27c5-11e8-8258-478b3ebec0b9.jpg)
![3](https://user-images.githubusercontent.com/6482545/37437694-10bd9bec-27c5-11e8-98fe-0e2d0c976718.jpg)

**Project Setup**

create-react-app nba-web


cd nba-web

npm install -S nba


npm install -S d3-shotchart


npm start 
| --- |

**Main parts of application**

**TopNavBar**

**ShotChart**

**Profile**

**Libraries**

[https://ant.design/components/radio-cn/#header](https://ant.design/components/radio-cn/#header)

**Ant Design**

| npm install -S antd |
| --- |

Import css lib



![4](https://user-images.githubusercontent.com/6482545/37437695-10cf16f6-27c5-11e8-9c16-0e892870677d.jpg)


**Lodash**

| npm install -S lodash |
| --- |

**Steps of development**

**ShotChart Fix**

**Shift ShotChart Up**

**Wrap DataViewContainer**

**Add CountSlider(antd, local state? lift state? both?)**

**Make Slider Work**

**Add Debouce(lodash)**

**Add SearchBar**

**Get Player Data(nba.searchPlayers())**

**Make Seach Work**

