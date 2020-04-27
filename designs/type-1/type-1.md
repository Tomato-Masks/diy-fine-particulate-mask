<html>
<head>
<style>
table, th, td {
  border: 0px solid black;
}
th, td {
  padding: 10px;
}
td {
    width:50%;
}
table.dimensions, th.dimensions, td.dimensions {
    border: 1px solid black;
    max-width: 100%;
    height: auto;
}
th.dimensions, td.dimcol1, td.dimcols{
    padding: 10px;
    border: 1px solid black;
}
tr.dimensions {
    vertical-align: middle;
}
td.dimcol1 {
    width: 40%;
    text-align: right;
    font-weight: bold;
    vertical-align: middle;
}
td.dimcols {
    width: 20%;
    text-align: center;
    vertical-align: middle;
}
//width: 400px;
//height: 301px;
img.tbl {  
  max-width:100%;
  height:auto;
}
// Adding 'Contents' headline to the TOC
#markdown-toc::before {
    content: "Contents";
    font-weight: bold;
}
// Using numbers instead of bullets for listing
#markdown-toc ul {
    list-style: decimal;
}
#markdown-toc {
    border: 1px solid #aaa;
    padding: 1.5em;
    list-style: decimal;
    display: inline-block;
}
</style>
</head>
</html>

**Type 1: DIY Fine Particulate Mask v0.4 (Current)**

**By Tomato Masks**

**Authors: Parsian Asgari, Allan Fernandes**

**Disclaimer**

This is a ‘Do It Yourself’ open source mask and we are not liable or responsible in regards to its performance or characteristics or how it is used. Build and use this at your own risks. 

**NOTE: This is not a respirator.**

**WARNING: Masks can be dangerous to people with respiratory or heart problems.**

# Objective

The objective here is to use available peer reviewed publication to design a mask that can be built at home with readily available materials and tools. 

There is evidence that homemade masks may help with reducing the likelihood of infection but not eliminate the risk.<sup>1 </sup>The goal here is not to eliminate the chance of inhaling fine particulates, droplets and aerosol but provide an extra layer of protection to:



1. Provide an extra barrier on the user’s face to reduce the chance of them touching their face
2. Reduce propagation of particulates from cough and sneeze
3. Through filtration, reduce the chance of inhaling some of the particles.
4. To provide the best possible homemade solution as a last resort where alternatives are not accessible or reserved for frontline workers.

# Background

The filtering systems used by respirators and masks have the ability to filter diverse particle sizes while maintaining breathability. Respirator filter design is always a tradeoff between breathability and filtration performance. 


## Filtration Mechanisms

There are three mechanisms involved in the filtration process of respirators and masks. These are inertial impaction, diffusion, and electrostatic attraction<sup>2</sup>:


### Inertial Impaction

Particles with a diameter of 1 µm and larger have higher inertia due to their mass<sup>2</sup>. Such particles are less likely to change path as they propagate along the airstream. As airstream flows through filtering material, complex airflow patterns are formed and that increases the need for maneuverability of particles in order to fall through the gaps. High inertial particles have lower tendency to change direction as a result, they impact the fibres of the filter<sup>2</sup>.


### Diffusion

Particles with a diameter of 0.1µm and smaller, have lower inertial and prone to influence by other particle interactions such as gas molecules. The momentum transfer leads to Brownian motion which increases the chance of collisions with the filter material’s fibres<sup>2</sup>.


### Electrostatic Attraction

Statically charged filters use electrostatic force to attract flowing particles of various sizes<sup>2</sup>. Many respirators use permanently charged fibres to entrap particles. The mechanism reduces the need for dense and thick filtration. 
<br>
<br>
<p align="center">
    <img src="./assets/images/type1v04/filtration-mechanism.jpg" width=450px>
</p>
<p style="text-align: center;">
<strong>Figure 1: Filtration Mechanisms<sup>2</sup></strong>
</p>
<br>

## Efficacy of Homemade Masks

The efficacy of masks depends on filtering efficiency as well as its airtightness. Filtration depends on many factors such as the size of the particles, their velocity, filter material structure and composition. Despite the filter material’s capability to block fine particulates, goodness of fit of masks is also important as aerosols can find their way through gaps where the mask fails to seal the face.<sup>1</sup> 

Filtration efficiency is a balance often comes at a cost of breathability. More dense materials tend to be less breathable and that has led to development of electrostatic filters.  

Since homemade masks are made with accessible items, materials and tools and no testing mechanisms are there to validate their performance, homemade masks should not be used as a respirator. Homemade masks should be only used as a last resort as they provide little protection.<sup>1</sup> 
<br>

# Design Requirements

1. Minimal tool and materials:
    1. This mask needs to be manufacturable with most commonly found household items
    2. Multiple options for materials should be available where possible.
2. This mask should be as accessible as possible:
    3. Easily constructible
    4. Easy instructions to follow
    5. Lowest possible material requirement
3. This mask should provide the best possible fit and be as snug as possible.


# Material Research

There are a few materials that can be used for filter and overall construction. The HEPA filters used by HVAC systems can be bought with PM 0.3 ratings. However, as such filters are not widely available and are expensive, alternative materials should also be pursued. Luckily, Cambridge University has done a study where they have ranked different household items in terms of their filtering capabilities. 

In their research, Davies A et al,<sup>1</sup> characterized a range of household materials and compared them with the material from a surgical mask from (Mo ¨lnlycke Health Care Barrier face mask 4239, EN14683 class I). 


## Filter Characterization

The researchers used circular cut outs of the materials and mounted them without any tension inside an airtight casing where the only entry point is through the material. They tested aerosol transport across each material. Through utilization of Henderson apparatus, the researchers delivered aerosols at a rate of 30L/min using the method of Wilkes et al,<sup>3</sup> which is equivalent of 3 to 6 times per minute the ventilation of human at rest or doing light work but is less than 0.1 the flow of an average cough.<sup>1</sup> 

In order to track filter material’s efficiency, the Cambridge University researchers used an apparatus to introduce the following microorganisms into the aerosol:



1. Bacillus atrophaeus with size ranges of 0.95 -1.25 µm
2. Bacteriophage MS2 with a diameter of 0.023 µm  

Using the apparatus, these microorganisms were later collected from the aerosol prior to the passage and after the passage. They would then analyze the samples and compare the results with a control setup where no filters were present. They repeated the process 9 times per each filter material.<sup>1</sup>

### Filter Efficiency

Davies A et al, then defined Filter Efficiency (FE) as the percent difference between colony-forming units (cfu) for upstream and downstream<sup>1</sup> as: 
<br>
<p align=center>
<a href="https://www.codecogs.com/eqnedit.php?latex=FE=&space;\frac{Upstream\&space;cfu&space;-&space;Downstream\&space;cfu}{Upstream\&space;cfu}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?FE=&space;\frac{Upstream\&space;cfu&space;-&space;Downstream\&space;cfu}{Upstream\&space;cfu}" title="FE= \frac{Upstream\ cfu - Downstream\ cfu}{Upstream\ cfu}" /></a>
<p>
<br>

### Filter Breathability

The breathability was evaluated through measurement of the pressure drop across either side of the filter casing while clean aerosol was delivered. The pressure was measured using a manometer (P200UL, Digitron).<sup>1</sup>

### Filter Performance

Davies et al study showed that all materials that were tested have some capability to block the microbial aerosols. However across the board, the materials performed 10% worse for Bacteriophage MS2. Those materials that performed really well suffered from breathability with the exception of the surgical mask that was used as a control. In the study, double layering of some materials were also tested<sup>1</sup>: