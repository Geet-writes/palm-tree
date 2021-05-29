---
createdOn: 22May
title: topic
layout: demo_template
link: topics/new
---

{% include exampleFor_includes.txt%}
{% include puppy.jpg%}

#  Conserve Water, Conserve Life!

## _Rainwater Harvesting for Homes_

adding a new line

[this is a link for a file within a topics folder]({{page.link}})

Following is the 'for' loop used to render data from 'data' csv file:

{% for item in site.data.data%}
-  {{item:name}}, {{item:age}}
{% endfor %}

**“Water is the driving force of all nature”**, as exclaimed by Leonardo da Vinci. With the life force that is becoming increasingly scarce by the day, it is no wonder that humans find it necessary to undertake expeditions to discover water on other planets.

## Why Rainwater Harvesting?

- Water comprises 70% of the Earth, but only 3% of it is fresh water which is trapped in frozen glaciers and underground currents which are inaccessible to humans.
- Surface water resources such as, rivers and lakes are being over-exploited and polluted, resulting in lower availability of usable water.

### What is Rainwater Harvesting

> (This is to show block quote) Rainwater harvesting is a means to `collect` and ~store~ rainwater at its source, that would otherwise be run-off resulting in wastage. Systems to harvest _rainwater_ can be installed for domestic, industrial and agricultural use.

#### Rainwater Harvesting for Homes -

1. Getting started
    -  A survey is done to determine the amount of rainwater that can be collected from the roof and other open areas around the house.
    -  If harvested rainwater is intended to be used for household purposes, filtration and pumping systems are required
        - Depending upon the collection capacity and intended use of rainwater, sloped gutters, downspouts, storage containers or cisterns, filtration device, submersible pump, distribution pipes and other plumbing materials are acquired.
1. Installing the Rainwater Harvesting System
    - **Catchment**:
      Mainly a rooftop acts as a catchment area for the rainwater. Rooftop needs to be clean, leak-proof and properly sloped. It is to be lined from outside with gutters and downspouts where needed. Run-off water from the roof collects in the gutters and is drained in the downspouts.
    - **Conveyance**
     Downspouts are further connected into a network of pipes that ultimately empty in the storage tank. Filtration devices such as, gutter guards, downspout filters and ‘first-flush’ system can be incorporated in the conveyance network before it empties into the storage tank

``` (This is used to show a code block) Submersible pump is to be installed inside the storage tank and outlet pipes connected to the tank to carry the water to the house’s plumbing system. Suitable kind of   purification treatment is advisable before the water is fit for use ```

**Participants table**
Name | Age | gender |
--- | --- | ---

-------
Date {{page.createdOn}}