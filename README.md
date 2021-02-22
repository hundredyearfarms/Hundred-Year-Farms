## Overview

Hundred Year Farms refers to two small farm properties (each about 43 acres); one on Prince Edward Island and the other in Manitoba. For both farms our plan is to make a gradual transition to Agroforestry.  Agroforesty involves the planting of crops, including grains, fruits, or vegetables, between rows of trees.  We believe that, over the long-term, this type of farming can be made so that it becomes carbon-negative, rebuilds topsoil, and maintains habitat even as climate changes. That, in turn, should lead to higher long-term asset values than would otherwise be the case, while making the farms more interesting and more enjoyable to visit for the next 100 years.

- [What is agroforestry?](https://www.aftaweb.org/)
- [Agroforestry - Canada](https://www.agr.gc.ca/eng/agriculture-and-climate/agricultural-practices/agroforestry/?id=1177431400694), [Agroforestry - UK](https://www.agforward.eu/index.php/en/silvoarable-agroforestry-in-the-uk.html), [Agroforestry - EU](https://euraf.isa.utl.pt/welcome), [Agroforestry - US](https://www.usda.gov/topics/forestry/agroforestry)

## Farm Plan (PEI)

Our plan for the island farm, as shown by the superposition of trees onto the sattelite image below, is to plant strong wind-break trees along the uppermost ridge with the trees and crops that require more sunlight and wind protection located lower on the farm's south sloping land. The existing trees are a near single species of spruce resulting from a prior clear-cut, but the new trees will be a diverse mix that may include maple, oak, poplar, birch, hemlock, and apple, among others.  The trees in rows will be arranged to allow for selective harvesting while some blocks will be left to grow unmanaged.  

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/IFCSite-FarmProposedTrees.png" alt="Farm plan - tree overlay" width="500">
</p>

<u>Image</u>: *Proposed new trees and storm-water collection pond laid over a sattelite image of the existing property on Prince Edward Island (gradient lines show how the land slopes toward the south where surface run-off water collects). A - water erosion down the centre of this field is already evident, but can be controlled by the new rows of trees that follow field contours. B - this prior clear-cut will be diversified to a range of native tree species. C - there will be relatively little change to this field apart from re-aligning the existing windbreak so it follows natural contours and then adding a second row at the lowest and steepest part of the field. D - Greenhouse.*

Some reasons for our transition to agroforestry are listed below:

- Productivity: Trees will reduce the higher wind speeds expected in the future and they will slow drainage from more extreme rainfall, both of which will help control soil erosion.  The lower wind speeds will also reduce damage to wind sensitive crops and, while increased tree shade will slow the growth of some crops, it will be beneficial to others as mid-afternoons become hotter. 

- Biodiversity: Mitigates climate induced pest and fire risks while making the property more interesting to live on or visit.  

- Diversified outputs: Greenhouses and higher-value trees can provide income independent of field crops.  
  
- Timing: Higher-value trees should be planted before changes to climate make them more difficult to establish.  

## Management

We are, or plan to, use these methods for managing our agroforesty practice.

**BIM (Building Information Management)**

Building Information Management (BIM) tools are being used for design of out-buildings (greenhouses, sheds, workshop, garage, ...).  These use sloped-roof buildings that can be combined to form larger buildings if needed.  For example, a tool for quickly converting a simple mark-down text document to a model suitable for visualization and costing (but not construction) is illustrated below.

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/slopedRoofFromSpecSheet-githubReadme.png" alt="Farm plan co-gen" width="500">
</p>

The main goal of BIM in our case, however, is to manage the farm's asset data over time (e.g. trees, soil conditions, crop yields, and infrastructure) using a 3D file system.  This makes large collections of data easier to store, find, and analize when compared to using conventional 2D folder arrangements. The use of BIM in this manner is now possible due to industry expanding the underlying BIM file system from buildings to include ([infrastructure and landscaping](https://www.buildingsmart.org/ifc-for-site-landscape-and-urban-planning-call-for-participation/)).  The IFC5 standard should be especially useful in regions where it is used by local government for the surrounding public works (roads, drainage, other infrastructure). 

This ability to record and then visually manage large amounts of agroforestry data over decades, using an open standard, and in a way that can transition to the next generation should prove useful as we work with consultants or with researchers modelling carbon-negative agroforestry systems.  This git repository will hold the workflow and associated FreeCAD/Blender models.

**Carbon negative cogeneration of heat, power, and treated water**

Small farm agroforestry produces waste biomass that, through gassification, can be used to produce heat (e.g. for greenhouses), electricity, treated water, and with some designs, fertilizer and [char](https://biochar-international.org/sustainability-climate-change/) (solid carbon) which can be used as a soil ammendment or sold as a [product](https://national-carbon.com/). A schematic showing the long-term design objectives for our application that we are working towards is shown below.

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/biogassifier2021-02-12.png" alt="Farm plan co-gen" width="400">
</p>

The technologies for converting waste biomass to energy and products have received strong research and development support from governments where climate change is a priority.  This is because the technology is one of the very few that integrates with the natural environment, can realistically become carbon-negative, deployed at scale, and potentially provide all utility services in a sustainable manner.  A good summary of the research done in this area is provided by this [Energy and Environmental Science Article](https://pubs.rsc.org/en/content/articlepdf/2016/ee/c6ee00935b) from the Royal Society of Chemistry, with practical exmaples listed below.

- [Agroforestry for Biomass Production - Benefiting Canadians](https://www.aftaweb.org/latest-newsletter/temporate-agroforester/97-2008-vol-17/april-no-1/74-agroforestry-for-biomass-production-benefiting-canadians.html)
- [Practical example - heat and electricity at Scotston Farm](https://www.youtube.com/watch?v=i9xmWJ4hAGs)
- [Practical example - heat and char at Burt's Greenhouse](https://biochar-international.org/burtsgreenhouse/)
- [Practical example - heat and char by the City of Stokcholm](https://www.stockholmvattenochavfall.se/en/current-projects/development/biochar/#!/about-the-biochar-project)
- [Commercial scale heat, electricity, and char](https://www.reset-energy.com/en/syngasmart-plants-use-cases-applications-and-benefits/)
- [Farm scale 25kW heat, electricity, and char](https://www.allpowerlabs.com/products/product-overview)

While the technology is promising, it generally remains cost-prohibitive.  Some cost-reduction will be achieved over the next few decades through improvements to equipment and system design, but these reductions are likely to be marginal and slow.  A new opportunity for significant cost reduction through improvements to the way in which project capital is raised and managed has recently emerged and is described under the heading for Smart Contracts below.  We have been studying this opportunity for years and will continue to see if it can be used as our application develops.

**Smart Contracts**: Smart (automated) contracts could be used to help manage project capital and that could make carbon-negative technologies more cost competitive. The paper listed below from the US Federal Reserve (St Louis), the OASIS Standards Body - Baseline Protocol, and the Ernst & Young blockchain intiative summarize the opportunities and tools most relevant to our project. 

- [US Federal Reserve - Smart Contract Research Report](https://research.stlouisfed.org/publications/review/2021/02/05/decentralized-finance-on-blockchain-and-smart-contract-based-financial-markets)
- [OASIS Standards Body - Baseline Protocol for Smart Contracts](https://docs.baseline-protocol.org/baseline-protocol/architecture)
- [Ernst & Younge Blockchain Initiative](https://blockchain.ey.com/)

The diagram below illustrates where we see smart contracts being implemented within the project process.

<p align="center">
<img src="https://raw.githubusercontent.com/hundredyearfarms/Hundred-Year-Farms/main/SMARTCONTRACTS.svg" alt="Smart Contract Cooperatives" width="800">
</p>
All of the smart contract platforms are still in early development and may require a decade or more to mature and become widespread, but they are far enough along today to begin serious evaluation of their potential in project work.  

**Schedule**:  Described above is our project concept which, over the course of 2021, will be refined with the help of consultants.  Following that will be a feasibility review that considers the state of technology (e.g. gassification, smart contracts) as well as government regulations and carbon related tax treatments.  The feasibility review is not expected to change our overall concept for carbon-negative agroforestry, but rather will tell us how quickly the above project can be implemented and the scope of our activities.  That implemenation very well may end up being within this decade or we may need to plan for a very gradual inter-generational transition to carbon-negative agroforestry.  Following feasibility will be the preliminary designs, then the down-selected detailed design, then implementation.     

## Owners

Nancy and Brenon Knaggs both grew up on small farms. During their working careers Nancy helped manage new technology product development. Brenon worked in the engineering design of low-carbon cogeneration power systems and later in project management for large public infrastructure projects. They both have a keen interest in the relation between small farms, communities, and biodiversity within a time of changing climate and technology. They can be contacted by email at "hun....yearfarms@protonmail.com"

