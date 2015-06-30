<!DOCTYPE html>
<html>
<title>Protocol1: Fungicide Sensitivity</title>
<xmp theme="Readable" style="display:none;">

##Fungicide Sensitivity Determination For *Fusarium* species using poison plate method

Prepared by: Jie Wang
Version: 0.1 (June 19 2015)

###Background
- *Fusarium* species causing sudden death syndrome or bean
    root rot symptoms on soybean and drybeans
- Fungicide seed treatment became an effective mean of disease management
  strategy for SDS, especially with the fungicide fluopyram (Brandname:
  [ILeVo](https://www.bayercropscience.us/products/seedgrowth/ilevo))
- *in vitro* efficacy of fluopyram on *Fusarium* species is still not clear
- Fluopyram is a Succinate Dehydrogenase Inhibitor (SDHI) fungicide widely used
    in agriculture and horticulture
- This protocol is also applicable with other fungicide sensitivity test
    against *Fusarium* species.

###Supplies and Preparation
1. Prepare fungicide stock solutions (Hands-on time: 1 hr)
  - Determine active ingredient according to fungicide label
  - [**Luna Privilege** Label](http://www.agrian.com/pdfs/Luna_Privilege_Label2.pdf)
    Active ingredient: Fluopyram (41.5%)
  - Stock solution concentrations: **0, 0.5, 1, 3, 5, 7, 10, and 50 mg/mL**
  - Detailed dilution protocol: See attached [excel spreadsheet](/lab_protocols/docs/fluopyram_stock_calculation.xlsx)
2. Media Preparation (Hands-on time: 2 hr, wait time: 2 hr)
  - 1/2 strength Potato Dextrose Agar (PDA)
  - Recipe ingredients include: 12 g of Potato dextrose broth, 15 g of agar,
    and 1 L dH2O
  - **[CAUTION!]** Put a magnetic stir bar in the media flask to homogenize media,
    and be sure to leave the magnetic bar in the flask while autoclave. Turn on
    water bath and adjust temperature to 55ºC
  - Autoclave media at 121ºC for 45 min (Wait about 1.5~2 hr)
  - When autoclaved media cool down to 55ºC, add 1 mL of fungicide stock solution
    into corresponding media flask and homogenize for 30 s with the magnetic
    bar already in the flask
3. *Fusarium* isolate transfer (Hands-on time: 1 hr, wait time: 10 d)
  - Transfer 13 *Fusarium* spp. isolates from slants to 1/2 strength PDA media
  - The most active growing point of Fungi is on the margin of the colony,
    where fungal hyphal tip is.
  - Colony cutting diagram (Figure 1)
  ![Colony cutting](/lab_protocols/img/Colony_Cubes.png)
  - Place the cutting cubes upside down on a new 1/2 PDA media
  - incubate the *Fusarium* colony at 25ºC for 10 d in the dark
4. Scanning protocol (Hands-on time: 40 min)
  - Place six plates on the scanner, and place a [scale bar](http://web.ncf.ca/jim/scale/)
    on the lower corner of the scanner
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
   air dry in the laminar flow hood overnight to dry the condensation water

2. [**Day2**] Cut *Fusarium* colony from the margin of the colony (Figure 1), and transfer
   upside down on a new 1/2 strength PDA media. Wrap the plate with parafilm and
   incubate the culture at 25ºC in a incubator. While incubating in the incubator,
   plates are placed upside down to avoid condensation water on the lids

3. [**Day4**] Scan plates from the bottom of the plates to measure the fungal colony
   to measure fungal colony growth area

4. [**Day11**] Scan plates to obtain the final area of *Fusarium* colony 10 days
   after transferring. Make sure data are all properly collected and autoclave petri
   dish and dispose biohazardous materials.

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

###References

</xmp>
<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
</html>
