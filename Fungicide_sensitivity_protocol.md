<!DOCTYPE html>
<html>
<title>Protocol1: Fungicide Sensitivity</title>
<xmp theme="Readable" style="display:none;">

##Fungicide Sensitivity Determination For *Fusarium* species using poison plate method

Prepared by: Jie Wang

Version: 0.3 (July 7 2015)

###Background
- *Fusarium* species causing sudden death syndrome or bean root rot symptoms on
  soybean and drybeans are of the most yield limiting plant pathogens worldwide
- Fungicide seed treatment is an effective mean of disease management
  strategy for SDS, especially with the fungicide fluopyram (Brandname:
  [ILeVo](https://www.bayercropscience.us/products/seedgrowth/ilevo))
- However, *in vitro* efficacy of fluopyram on *Fusarium* species growth inhibition
  is still not clear
- Fluopyram is a Succinate DeHydrogenase Inhibitor (SDHI) fungicide widely used
  in agriculture and horticulture


###Supplies and Preparation
1. Fungicide stocks preparation (Hands-on time: 1 hr)
  - Determine active ingredient according to fungicide label
  - [**Luna Privilege** Label](http://www.agrian.com/pdfs/Luna_Privilege_Label2.pdf)
    Active ingredient: Fluopyram (41.5%)
  - Stock solution concentrations: **0, 0.5, 1, 3, 5, 7, 10, and 50 mg/mL**
  - Detailed dilution protocol: See appendix below
2. Media Preparation (Hands-on time: 2 hr, wait time: 2 hr)
  - 1/2 strength Potato Dextrose Agar (PDA)
  - Recipe ingredients include: 12 g of Potato dextrose broth, 15 g of agar,
    and 1 L dH2O
  - **[CAUTION!]** Put a magnetic stir bar in the media flask to homogenize media,
    and be sure to leave the magnetic bar in the flask while autoclave. Turn on
    water bath and adjust temperature to 55ºC
  - Autoclave media at 121ºC for 45 min (Wait time: 1.5~2 hr)
  - When autoclaved media cool down to 55ºC, add 1 mL of fungicide stock solution
    into corresponding media flask and homogenize for 30 s at low speed with the
    magnetic bar already been put in the flask

3. *Fusarium* isolate transferring (Hands-on time: 1 hr, wait time: 10 d)
  - Transfer 13 *Fusarium* spp. isolates (12 new isolates + 1 reference isolate Mont-1)
    from slants to 1/2 strength PDA media
  - The most active growing point of Fungi is on the tip of a hyphae, where is
    the margin of the colony
  - Colony cutting diagram (Figure 1)

<img src="/lab_protocols/img/Colony_Cubes.png" alt="Colony cutting" align="middle">

  Cut the colony from the margin of the colony and transfer the small individual
  cubes to the new 1/2 strength PDA plates. The size of transferred plugs is
  approximately 4 mm^2 wide

  - Place the cutting agar upside down on a new 1/2 PDA media
  - incubate the *Fusarium* culture at 25ºC for 10 d in the dark
4. Scanning protocol (Hands-on time: 40 min)
  - Place six plates on the scanner, and place a [scale bar](http://web.ncf.ca/jim/scale/)
    (http://web.ncf.ca/jim/scale/) on the lower corner of the scanner
  - Scan file nomination systems: {Isolate Name}_{Concentration1}_{Concentration2}ppm.jpg.
    Use underscore (" _ ") only.
  - For example: ARLE_C1_5_1ppm.jpg, ARLE_C1_50_10ppm.jpg, ARLE_C1_200_100ppm.jpg,
    and ARLE_C1_ck.jpg.
  - Background color for scanning plates is dark blue (Hex-color code: #1E2E4D)


###Procedures

Note: Detailed procedures refer to the supplies and preparation step

1. [**Day1**] Make 7 L of 1/2 stength PDA media amended with 1 mL corresponding fungicide
   stock solutions, and pour media into 9-cM petri dishes. Normally, 1 L of 1/2
   PDA media should fit with 40 petri dishes (2 bags). Let the petri dish plates
   air dry in the laminar flow hood overnight to remove the condensation water

2. [**Day2**] Cut *Fusarium* colony from the margin of the colony (Figure 1), and transfer
   upside down on a new 1/2 strength PDA media with 3 replicates. Wrap the plate with parafilm and
   incubate the culture at 25ºC in a incubator. While incubating in the incubator,
   plates are placed upside down to avoid condensation water formed on the lids

3. [**Day4**] Scan plates from the bottom of the plates to measure the fungal colony
   to measure fungal colony growth area

4. [**Day11**] Scan plates to obtain the final area of *Fusarium* colony 10 days
   after transferring. Make sure data are all properly collected. Autoclave petri
   dishes and dispose biohazardous materials.

###Data Analysis
1. All images were analyzed in APS Assess v2.0 using the manual panel and setting
   the HSV color space to select the colony using hue value between 0 and 195 with
   the dark blue background (hex color code:#1E2E4D).
2. Relative mycelial growth rate was calculated by subtracting the 3 DAI colony
   area from the 10 DAI colony area and divided by seven days to get the colony
   area increase per day.
3. The effective concentration to reduce growth by 50% (EC50[ subscript]) for
   each isolate was calculated by fit the mycelia relative growth rate against
   the fungicide concentrations using a 4-parameter log-logistic model
   with [**drc** v2.5](http://cran.r-project.org/web/packages/drc/index.html)

###Appendix
- Fungicide stock preparation
*Table* Fungicide stock concentration preparation using Luna Privilege as an example

<table border="1">
<tbody><tr><td>Target Concentration</td>
<td>Unit</td>
<td>Original (mL)</td>
<td> </td>
<td>H2O (mL)</td>
</tr>
<tr><td>0.5</td>
<td>mg/mL</td>
<td> </td>
<td>2 mL of 10 mg/mL</td>
<td>38</td>
</tr>
<tr><td>1</td>
<td>mg/mL</td>
<td> </td>
<td>4 mL of 10 mg/mL</td>
<td>36</td>
</tr>
<tr><td>3</td>
<td>mg/mL</td>
<td>0.24</td>
<td> </td>
<td>39.76</td>
</tr>
<tr><td>5</td>
<td>mg/mL</td>
<td>0.4</td>
<td> </td>
<td>39.6</td>
</tr>
<tr><td>7</td>
<td>mg/mL</td>
<td>0.56</td>
<td> </td>
<td>39.44</td>
</tr>
<tr><td>10</td>
<td>mg/mL</td>
<td>0.8</td>
<td> </td>
<td>39.2</td>
</tr>
<tr><td>50</td>
<td>mg/mL</td>
<td>4.01</td>
<td> </td>
<td>35.99</td>
</tr>
</tbody></table>

First two columns indicate the target concentrations used in the fungicide stock;
the third column indicate the volume of original fungicide solution added to the
diluted stock solutions; the fourth column indicates the amount of 10 mg/mL of
stock solution needed for the 1 and 0.5 mg/mL stocks solutions; the last column
indicates the amount of water needed for the dilutions. Below is a diagram show
the process of how to make stock concentrations.


  ![Fungicide stock preparation](/lab_protocols/img/Fungicide_stock_prep.png)


- NOTE: This protocol was validated with *F. virguliforme* and a few closely related
 *Fusarium* spp., therefore is not warrant for extended experiments with other
 fungal species

###References


</xmp>
<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
</html>
