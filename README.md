
[<img src="https://crowd4sdg.eu/wp-content/uploads/2020/06/logo.png" title="Crowd4SDG Project's Website"  align="middle" width=250 />](https://crowd4sdg.eu/)

# Introduction to the Crowd4SDG Citizen Science Solution Kit

A citizen science (CS) project leader is a person, group of persons, or organization who is interested in carrying forward a CS project. The Citizen Science Solution Kit (CSSK) is a set of tools built, curated, and maintained by the [Crowd4SDG](https://crowd4sdg.eu) project with the objective to help a CS project leader to successfully advance a CS project. Each of the tools focuses on a common recurring need of CS project leaders given in the table below:

CS project leader needs to | Tool 
--- | --- 
Increase the involvement of citizens into the management of the project | decidim4CS
Enroll a volunteer community to perform a complex data classification task | Project Builder
Analyze data obtained from a volunteer community | Crowdnalysis
Extract visual evidence about a situation from images on Twitter,<br />filtering out irrelevant images, and geotagging them | VisualCit
Document the progress of the CS project | decidim4CS,<br />SDG in Progress


## A CSSK case story

The following story represents what a typical story of the usage of the CSSK toolkit could look like:

Jane Doe wants to start a Citizen Science project to help her community in Ruritania be better prepared in case a flooding occurs as a result of climate change. In order to understand what the needs of the community are, she uses [Decidim4CS](#decidim4cs), where she can easily set up a homepage and blog for the project, receive the proposals from the community, organize meetings and request citizens to vote. After three months of debating and self-organizing through Decidim4CS, it has been agreed with the community that better data is needed to make adequate decisions. In particular, they have co-decided that a map of the places which are more likely to get damaged when floods occur would be a very valuable asset for the project, and they are willing to work together to make it. They agree to build the map based on information of the last two floods that took place in Ruritania. By means of [VisualCit](#visualcit) they crawl the tweets containing images from those two floods, filter those images which do not contain images of the floods, and geolocate the tweets. After that, they are left with several thousand images. They create a project in [Project Builder](#project-builder), upload the images and request a set of volunteers to connect to Project Builder and help them classify the images by labeling them with one out of five different levels of damage. They decide that, to improve the quality of the data, each image will be labeled by five different volunteers. Once the volunteers have labeled all the images, they use [Crowdnalysis](#crowdnalysis) to provide them with advanced AI models to go from labels provided by each of the volunteers to a consensus opinion which takes into account the accuracy of the different volunteers, or specific characteristics of the images. After a consensus labeling is established for each image, VisualCit helps visualize a map coloring the different regions of Ruritania with different intensities based on their likelihood to get damage in a flood and visualizing the associated images from the last two floods. Based on the map, Jane decides….



# Crowd4SDG CSSK components

Current status of the tools are as below:

Tool | Current status
--- |:---:
Project Builder | Operational
VisualCit | Prototype
decidim4CS | Operational
Crowdnalysis | Prototype
SDG in Progress | Operational

## Project Builder

The [Citizen Science Project Builder](https://lab.citizenscience.ch) (PB) is a web-based tool that allows researchers, students, and all members of the public to create and run data-analysis for a CS project. Such projects may take many different forms, from classifying images of snakes to transcribing handwritten German dialect, from collecting samples of water to taking pictures of insects and plants. Typically, volunteer contributors are asked to perform complex data classification task (ie. classify, tag, describe, or geo-localize) that are still best performed by human minds and skills. In particular, the PB supports projects based on existing digital data that can be in the form of images, text, PDF documents, social media posts (tweets), sounds and video clips. The PB provides an interface that requires limited technical knowledge, and ideally little or no coding skills. 

## VisualCit

Getting first-hand information about an emergency situation while it is happening is important, but is often difficult to obtain in time. VisualCit, the image-based social sensing toolkit, allows extracting visual evidence about a situation from Twitter. It focuses on the selection, geolocalization and analysis of images extracted from Twitter.

Further details of the tool can be found [here](http://pernici.faculty.polimi.it/crowd4sdg-tools-polimi/). For the open-source software, please refer to [this](https://gitlab.iiia.csic.es/crowd4sdg/polimipipeline) code repository.

## decidim4CS

[decidim4CS](https://decidim4cs.ml) is a free digital platform for participatory citizen science and it constitutes the deliberation technology used in the Crowd4SDG project. It allows citizen scientists to involve democratically in science projects by providing a plethora of participation options, such as making proposals, scheduling public meetings, making decisions through different forms of voting, and monitoring the implementations of these decisions. decidim4CS is based on [decidim](https://decidim.org), a free open-source software created by the Barcelona City Hall as a participatory democracy platform for cities and organizations.

Open-source code of decidim4CS is available at [this](https://github.com/Crowd4SDG/decidim4cs) public GitHub repository. 

## Crowdnalysis

The main aim of Crowdnalysis is to ease the statistical analysis of the data gathered by the Project Builder, in order to help the scientist managing the CS project to get the most accurate information from the contributions of volunteers. Specifically, Crowdnalysis is an open-source software [library](https://github.com/Crowd4SDG/crowdnalysis) that provides advanced probabilistic consensus models to aggregate volunteer annotations in CS projects. Crowdnalysis is distributed as a Python package via [PyPI](https://pypi.org/project/crowdnalysis/).

## SDG in Progress

[SDG in Progress](https://sdginprogress.com) is a platform for anyone who wants to document projects they are carrying out towards tackling the UN Sustainable Development Goals (SDGs), or who wants to get inspired by other people’s projects, re-use them or re-purpose them. There are many ways to document projects: wikis, GitHub etc. The point of SDG in Progress is to build up an open repository of SDG projects, which may involve hardware and software development, or focus more on grassroots or policy initiatives. The idea is to inspire creativity, while minimizing redundancy.

### Funding

<img src="https://europa.eu/european-union/sites/europaeu/files/docs/body/flag_yellow_low.jpg" width="30" /> The Crowd4SDG project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No. 872944.

<!--
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Crowd4SDG/crowd4sdg.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
-->
