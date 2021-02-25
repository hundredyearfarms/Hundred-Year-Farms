## Overview

Hundred Year Farms refers to two small farm properties (each about 43 acres); one on Prince Edward Island and the other in Manitoba. For both farms our plan is to make a gradual transition to Agroforestry.  Agroforesty involves the planting of crops, including grains, fruits, or vegetables, between rows of trees.  We believe that, over the long-term, this type of farming can be made so that it becomes carbon-negative while it rebuilds topsoil and maintains habitat. That, in turn, should lead to higher long-term asset values than would otherwise be the case and make the farms more interesting to visit for the next 100 years.

- [What is agroforestry?](https://www.aftaweb.org/)
- [Agroforestry - Canada](https://www.agr.gc.ca/eng/agriculture-and-climate/agricultural-practices/agroforestry/?id=1177431400694), [Agroforestry - UK](https://www.agforward.eu/index.php/en/silvoarable-agroforestry-in-the-uk.html), [Agroforestry - EU](https://euraf.isa.utl.pt/welcome), [Agroforestry - US](https://www.usda.gov/topics/forestry/agroforestry)

## Farm Plan (PEI)

Our plan for the island farm, as shown by the superposition of trees onto the sattelite image below, is to plant strong wind-break trees along the uppermost ridge with the trees and crops that require more sunlight and wind protection located lower on the farm's south sloping land. The existing trees are a near single species of spruce resulting from a prior clear-cut, but the new trees will be a more diverse mix that may include maple, oak, poplar, birch, hemlock, and apple, among others.  The trees in rows will be arranged to allow for selective harvesting while some blocks will be left to grow unmanaged.  

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/IFCSite-FarmProposedTrees.png" alt="Farm plan - tree overlay" width="500">
</p>

<u>Image</u>: *Proposed new trees and storm-water collection pond laid over a sattelite image of the existing property on Prince Edward Island (gradient lines show how the land slopes toward the south where surface run-off water collects). A - water erosion down the centre of this field is already evident, but can be controlled by the new rows of trees that follow field contours. B - this prior clear-cut will be diversified to a range of native tree species. C - there will be relatively little change to this field apart from re-aligning the existing windbreak so it follows natural contours and then adding a second row at the lowest and steepest part of the field. D - Greenhouse.*

Some reasons for our transition to agroforestry are listed below:

- Productivity: Trees in rows will reduce the higher wind speeds expected in the future and they will slow drainage from more extreme rainfall, both of which will help control soil erosion.  
 
- Biodiversity: Mitigates climate induced pest and fire risks while making the property more interesting to live on or visit.  

- Diversified outputs: Greenhouses and higher-value trees can provide income independent of the field crop.  
  
- Timing: Higher-value trees should be planted before changes to climate make them more difficult to establish.  

## Management

We are using an open standard 3D file system for design and to manage the farm's data.  To improve the long-term economics of our agro-forestry project we are working towards using waste wood and crop waste to provide the farm's utilty services.  These are expanded upon below.

**Buildings, Infrastructure, and Landscaping (using BIM-IFC5)**

For buildings, some of the conventional Building Information Management (BIM) tools are being used to design out-buildings (greenhouses, sheds, workshop, garage, ...).  For example, one of the tools we use can quickly generate a model, that is suitable for visualization and costing, from a simple mark-down text document as illustrated below.

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/slopedRoofFromSpecSheet-githubReadme.png" alt="Farm plan co-gen" width="500">
</p>

The main purpose of BIM in our case, however, is to manage the farm's asset data over time (e.g. trees, soil conditions, crop yields, and infrastructure) using the BIM extension for [infrastructure and landscaping](https://www.buildingsmart.org/ifc-for-site-landscape-and-urban-planning-call-for-participation/) (known as BIM-IFC5).  This will make large collections of data, gathered over decades, easier to store, find, and analize when compared to using conventional 2D folder arrangements which can quickly become overwhelming and difficult for others to use.  

Use of the BIM-IFC5 standard should be especially useful to agroforestry projects in regions where that standard is also used by local government for the surrounding public works (roads, drainage, other infrastructure). This git repository will hold the workflow and associated FreeCAD/Blender models as they develop.

**Carbon-negative cogeneration of heat, power, and treated water**

Small-farm agroforestry produces significant amounts of waste biomass that must be managed.  Through gassification this waste can be used to produce heat (e.g. for greenhouses), gas, electricity, treated water, and with some designs, fertilizer and [char](https://biochar-international.org/sustainability-climate-change/) (solid carbon) which can be used as a soil ammendment or sold as a [product](https://national-carbon.com/). A schematic showing the long-term design objectives for our greenhouse integrated application is shown below.

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/biogassifier2021-02-12.png" alt="Farm plan co-gen" width="400">
</p>

The technologies for using waste wood and waste crop biomass to provide utility services have received strong research and development support from governments where climate change is a priority.  That is because the technology is one of the very few that integrates so completely with the natural environment, can realistically become carbon-negative, be fabricated by any modern country and deployed at scale, and sustainably provide all utility services.  A good summary of the core gassification technology is provided by this [Energy and Environmental Science Article](https://pubs.rsc.org/en/content/articlepdf/2016/ee/c6ee00935b) from the Royal Society of Chemistry, with practical examples of use listed below.

- [Agroforestry for Biomass Production - Benefiting Canadians](https://www.aftaweb.org/latest-newsletter/temporate-agroforester/97-2008-vol-17/april-no-1/74-agroforestry-for-biomass-production-benefiting-canadians.html)
- [Practical example - heat and electricity at Scotston Farm](https://www.youtube.com/watch?v=i9xmWJ4hAGs)
- [Practical example - heat and char at Burt's Greenhouse](https://biochar-international.org/burtsgreenhouse/)
- [Practical example - heat and char by the City of Stokcholm](https://www.stockholmvattenochavfall.se/en/current-projects/development/biochar/#!/about-the-biochar-project)
- [Commercial scale heat, electricity, and char](https://www.reset-energy.com/en/syngasmart-plants-use-cases-applications-and-benefits/)
- [Farm scale 25kW heat, electricity, and char](https://www.allpowerlabs.com/products/product-overview)

In our case, the availability of this technology encourages a transition to agroforestry (and the associated improvements to biodiversity and food production).  Without it, we are economically encourages to continue with mono-crop farming. However, while the core technology is mature and proven, practical systems generally remain cost-prohibitive.  Some cost-reduction will be achieved over the next few decades through improvements to equipment, but these reductions are likely to be marginal and slow.  The more significant cost reduction opportunities are likely to be those from:

1. Improve system integration to provide all utility services as illustrated above. 
1. Using Smart Contract platforms to lower the cost of capital and administrative overhead. 

Of these two, the smart (automated) contracts are judged to be the most important and, if successful, could make carbon-negative technologies in general more cost competitive and thus increase the rate of carbon sequestration. The paper listed below from the US Federal Reserve, the OASIS Standards Body - Baseline Protocol, and the Ernst & Young blockchain intiative summarize the opportunities and tools most relevant to our project. 

- [US Federal Reserve - Smart Contract Research Report](https://research.stlouisfed.org/publications/review/2021/02/05/decentralized-finance-on-blockchain-and-smart-contract-based-financial-markets)
- [OASIS Standards Body - Baseline Protocol for Smart Contracts](https://docs.baseline-protocol.org/baseline-protocol/architecture)
- [Ernst & Younge Blockchain Initiative](https://blockchain.ey.com/)

The first panel in the diagram below depicts conventional project financing from investor shares.  The second panel depicts a common, but less frequently used, form of financing for projects with a social purpose known as a cooperative.  The third panel improves upon the social purpose cooperative using smart contracts.    

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/SMARTCONTRACTS.svg" alt="Smart Contract Cooperatives" width="800">
</p>

A recent [low-carbon biogas-from-waste project](https://www.torontozoo.com/tz/biogas) at the Toronto Zoo (completed in 2021) used a project structure similiar to that in the second panel.  They were able to organize their project as a cooperative since the surrounding community viewed their project as having a social purpose and this allowed them to raise money by selling bonds to those in the surrounding area at 5% as opposed to the 15% or more that an investor led project would require.  For this $5M project, the difference between having to return capital at 5% versus 15% is significant.  The smart contract technology, as shown in the third panel, could further lower the cost of that approach especially for the smaller social purpose projects.

Note: The smart contract platforms are still in early development, but are far enough along to research their use in practical project work. 

## Schedule:  

We are at the concept design stage and over the course of 2021 will continue to refine it with the help of consultants.  Following that will be a feasibility study that considers the state of technology (e.g. IFC5, co-generation, and smart contracts) as well as government regulations and carbon related tax treatments.  The feasibility study is not expected to change our overall concept for carbon-negative agroforestry, but rather will tell us how quickly the greenhouse integrated co-generation system can be implemented and the scope of our activities.  Following feasibility will be the preliminary designs, then the down-selected detailed design, then implementation. Implemenation very well may end up being within this decade or we may need to plan for a more gradual inter-generational transition to carbon-negative agroforestry.  

## Owners

Nancy and Brenon Knaggs both grew up on small farms. During their working careers Nancy helped manage new technology product development. Brenon worked in the engineering design of low-carbon cogeneration power systems and later in project management for large public infrastructure projects. They both have a keen interest in the relation between small farms, communities, and biodiversity within a time of changing climate and technology. They can be contacted by email at "hun....yearfarms@protonmail.com"

