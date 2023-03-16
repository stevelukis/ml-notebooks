## MSSubClass: Identifies the type of dwelling involved in the sale.

        20	1-STORY 1946 & NEWER ALL STYLES
        30	1-STORY 1945 & OLDER
        40	1-STORY W/FINISHED ATTIC ALL AGES
        45	1-1/2 STORY - UNFINISHED ALL AGES
        50	1-1/2 STORY FINISHED ALL AGES
        60	2-STORY 1946 & NEWER
        70	2-STORY 1945 & OLDER
        75	2-1/2 STORY ALL AGES
        80	SPLIT OR MULTI-LEVEL
        85	SPLIT FOYER
        90	DUPLEX - ALL STYLES AND AGES
       120	1-STORY PUD (Planned Unit Development) - 1946 & NEWER
       150	1-1/2 STORY PUD - ALL AGES
       160	2-STORY PUD - 1946 & NEWER
       180	PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
       190	2 FAMILY CONVERSION - ALL STYLES AND AGES

The MSSubClass feature in the House Prices dataset identifies the type of dwelling involved in the sale. The feature has
discrete values that correspond to different categories of residential properties. The values and their corresponding
descriptions are:

- 20: 1-STORY 1946 & NEWER ALL STYLES - This refers to a single-story property that was built in 1946 or later, and can
  have any architectural style.

- 30: 1-STORY 1945 & OLDER - This refers to a single-story property that was built in 1945 or earlier, and can have any
  architectural style.

- 40: 1-STORY W/FINISHED ATTIC ALL AGES - This refers to a single-story property with a finished attic, which can be of
  any age.

- 45: 1-1/2 STORY - UNFINISHED ALL AGES - This refers to a one-and-a-half story property that is unfinished, and can be
  of any age.

- 50: 1-1/2 STORY FINISHED ALL AGES - This refers to a one-and-a-half story property that is finished, and can be of any
  age.

- 60: 2-STORY 1946 & NEWER - This refers to a two-story property that was built in 1946 or later.

- 70: 2-STORY 1945 & OLDER - This refers to a two-story property that was built in 1945 or earlier.

- 75: 2-1/2 STORY ALL AGES - This refers to a two-and-a-half story property that can be of any age.

- 80: SPLIT OR MULTI-LEVEL - This refers to a property with multiple levels, where each level is only a few steps above
  or below the adjacent level.

- 85: SPLIT FOYER - This refers to a property with a foyer or entrance area that is split between two levels.

- 90: DUPLEX - ALL STYLES AND AGES - This refers to a property that is divided into two separate living units.

- 120: 1-STORY PUD (Planned Unit Development) - 1946 & NEWER - This refers to a single-story property that is part of a
  planned unit development, and was built in 1946 or later.

- 150: 1-1/2 STORY PUD - ALL AGES - This refers to a one-and-a-half story property that is part of a planned unit
  development, and can be of any age.

- 160: 2-STORY PUD - 1946 & NEWER - This refers to a two-story property that is part of a planned unit development, and
  was built in 1946 or later.

- 180: PUD - MULTILEVEL - INCL SPLIT LEV/FOYER - This refers to a property with multiple levels that is part of a
  planned unit development, and includes split levels and split foyers.

- 190: 2 FAMILY CONVERSION - ALL STYLES AND AGES - This refers to a property that has been converted into two separate
  living units, and can be of any age or style.

The MSSubClass feature provides information about the type of property being sold, and can be used to gain insights into
how different types of properties may be priced differently or have different features that impact their value. For
example, it may be the case that single-story properties are more valuable than multi-story properties, or that
properties in planned unit developments are priced differently than standalone properties.

---

## MSZoning: Identifies the general zoning classification of the sale.

       A	Agriculture
       C	Commercial
       FV	Floating Village Residential
       I	Industrial
       RH	Residential High Density
       RL	Residential Low Density
       RP	Residential Low Density Park 
       RM	Residential Medium Density

MSZoning refers to the general zoning classification of the property where the house is located. Zoning is a process by
which local governments regulate land use and development to ensure that it is consistent with the overall community
plan.

The different zoning classifications in the MSZoning feature are as follows:

- A: Agriculture zoning refers to land that is primarily used for agricultural purposes such as farming, crop
  production, or livestock grazing.

- C: Commercial zoning refers to land that is designated for commercial activities such as retail stores, offices,
  restaurants, and hotels.

- FV: Floating Village Residential zoning refers to land that is designated for residential use, typically on water.

- I: Industrial zoning refers to land that is designated for industrial activities such as manufacturing, warehousing,
  or transportation.

- RH: Residential High Density zoning refers to land that is designated for residential use with high-density housing
  options such as apartments, condominiums, or townhouses.

- RL: Residential Low Density zoning refers to land that is designated for residential use with low-density housing
  options such as single-family homes on large lots.

- RP: Residential Low Density Park zoning refers to land that is designated for residential use with recreational spaces
  and parks included.

- RM: Residential Medium Density zoning refers to land that is designated for residential use with medium-density
  housing options such as duplexes, triplexes, or smaller apartment buildings.

---

## LotFrontage: Linear feet of street connected to property

LotFrontage is a feature that represents the linear feet of the street connected to the front of the property. In other
words, it refers to the length of the boundary between the front of the property and the street.

For example, if a house is situated on a rectangular lot and the front side of the lot faces the street, then the
LotFrontage would represent the length of the side of the lot that is connected to the street. If the lot is irregularly
shaped or the front of the lot does not directly face the street, then the LotFrontage may be an estimate or
approximation of the linear feet of street connected to the property.

LotFrontage can be an important feature in determining the value of a property as it can affect the accessibility and
visibility of the property from the street, which may influence potential buyers' preferences and willingness to pay for
the property.

---

## LotArea: Lot size in square feet

LotArea is a feature that represents the size of the lot on which the property is situated, measured in square feet. It
refers to the total area of the land that the property occupies, including any buildings, structures, or landscaping
within the boundaries of the lot.

For example, if a property is situated on a rectangular lot that measures 100 feet by 150 feet, then the LotArea would
be 15,000 square feet (100 feet x 150 feet). LotArea can be an important factor in determining the value of a property
as it can indicate the amount of outdoor space available for use, as well as the potential for development or expansion
of the property. However, it should be noted that LotArea alone may not fully capture the value of a property, as other
factors such as location, amenities, and condition of the property may also play a significant role in determining its
value.

---

## Street: Type of road access to property

       Grvl	Gravel	
       Pave	Paved

Street is a feature that represents the type of road access to the property. It can take on one of two values: Grvl or
Pave.

- Grvl: This value indicates that the property is accessed by a gravel road. Gravel roads are typically made up of
  crushed rock or gravel, and can be found in rural areas or areas with lower traffic volume.

- Pave: This value indicates that the property is accessed by a paved road. Paved roads are typically made up of
  concrete or asphalt and can be found in urban or suburban areas.

The value of the Street feature can be important in determining the value of a property, as properties with access to
paved roads may be considered more desirable due to factors such as ease of access, smoother driving conditions, and
potentially higher property values in the surrounding area.

---

## Alley: Type of alley access to property

       Grvl	Gravel
       Pave	Paved
       NA 	No alley access

The Alley feature in the dataset represents the type of alley access to the property and can take on one of three
values: Grvl, Pave, or NA.

- Grvl: This value indicates that the property is accessed by an alley that is surfaced with gravel.

- Pave: This value indicates that the property is accessed by an alley that is paved with concrete or asphalt.

- NA: This value indicates that the property does not have alley access.

The type of alley access can be important in determining the value of a property, as properties with alley access may be
considered more desirable due to factors such as additional parking or garage space and potentially easier access to the
property. The quality of the alley access, whether it is gravel or paved, may also impact the property value.

---

## LotShape: General shape of property

       Reg	Regular	
       IR1	Slightly irregular
       IR2	Moderately Irregular
       IR3	Irregular

The LotShape feature in the dataset describes the general shape of the property and can take on one of four values:

- Reg: This value indicates that the property is a regular shape, typically a rectangle.
- IR1: This value indicates that the property is slightly irregular in shape.
- IR2: This value indicates that the property is moderately irregular in shape.
- IR3: This value indicates that the property is irregular in shape.

The shape of a property can impact its value, as properties with regular shapes may be easier to build on and may be
more desirable for some buyers. However, irregularly shaped properties may offer unique features or be located in
desirable areas, which could increase their value. The impact of lot shape on property value is likely to be
context-dependent and may vary depending on the local real estate market.

---

LandContour: Flatness of the property

       Lvl	Near Flat/Level	
       Bnk	Banked - Quick and significant rise from street grade to building
       HLS	Hillside - Significant slope from side to side
       Low	Depression

The LandContour feature describes the flatness or slope of the property, and can take on one of four values:

- Lvl: This value indicates that the property is near flat or level. This is the most desirable type of land contour, as
  it provides a stable and level foundation for building.
- Bnk: This value indicates that the property is banked, with a quick and significant rise from the street grade to the
  building. This type of land contour can be challenging for construction, as it may require significant excavation or
  the use of retaining walls.
- HLS: This value indicates that the property is on a hillside, with a significant slope from side to side. This type of
  land contour can offer scenic views and may be desirable for some buyers, but can also pose challenges for
  construction and landscaping.
- Low: This value indicates that the property is in a depression, with a lower elevation relative to the surrounding
  area. This type of land contour can also pose challenges for construction and landscaping, and may be less desirable
  for some buyers.

The impact of land contour on property value can depend on a number of factors, including the local real estate market
and the preferences of potential buyers. In general, properties with flat or near-flat land contours may be more
desirable and easier to build on, while properties with steep slopes or other irregular features may require more work
and investment to develop. However, unique features such as scenic views or natural features may also add value to
properties with more challenging land contours.

---

## Utilities: Type of utilities available

       AllPub	All public Utilities (E,G,W,& S)	
       NoSewr	Electricity, Gas, and Water (Septic Tank)
       NoSeWa	Electricity and Gas Only
       ELO	Electricity only	

- AllPub: All public utilities (electricity, gas, water, and sewer) are available to the property. This is the most
  desirable option as it provides the highest level of convenience and comfort to the homeowner. Properties with AllPub
  utilities generally have a higher value than those without.
- NoSewr: The property is connected to electricity, gas, and water, but does not have access to a public sewer system.
  Instead, it uses a septic tank for waste disposal. This can be a disadvantage as septic tanks require regular
  maintenance and can be costly to repair or replace. However, in some rural areas, this may be the only option
  available. Properties with NoSewr utilities may have a slightly lower value than those with AllPub utilities.
- NoSeWa: The property is connected to electricity and gas only, and does not have access to public water or sewer
  systems. This can be a significant disadvantage as it means that the property relies on a well for water supply, which
  can be less reliable and may require regular testing and maintenance. Properties with NoSeWa utilities may have a
  lower value than those with AllPub or NoSewr utilities.
- ELO: The property is only connected to electricity and does not have access to gas, water, or sewer systems. This is
  the least desirable option as it provides the lowest level of convenience and comfort to the homeowner. Properties
  with ELO utilities may have a significantly lower value than those with AllPub or NoSewr utilities.

---

## LotConfig: Lot configuration

       Inside	Inside lot
       Corner	Corner lot
       CulDSac	Cul-de-sac
       FR2	Frontage on 2 sides of property
       FR3	Frontage on 3 sides of property

Lot configuration is a feature that refers to the shape and location of the lot on which the house is built. Here are
some possible impacts that each category may have on the house price:

- Inside: An inside lot is surrounded by other lots on all sides, meaning there are neighbors on either side of the
  house. This may have a neutral or slightly negative impact on house prices, as some buyers may prefer more privacy and
  space between their house and their neighbors.
- Corner: A corner lot is situated at the intersection of two streets and has more space between the house and
  neighboring lots. This may have a positive impact on house prices, as it provides more privacy and curb appeal.
- Cul-de-sac: A cul-de-sac lot is situated at the end of a dead-end street and typically has less traffic and noise than
  other lots. This may have a positive impact on house prices, as it provides a quieter and more peaceful setting.
- FR2: A lot with frontage on two sides of the property may have more versatility in terms of access and orientation of
  the house. This may have a neutral or slightly positive impact on house prices.
- FR3: A lot with frontage on three sides of the property may have even more versatility and flexibility in terms of
  house orientation and access. This may have a neutral or slightly positive impact on house prices.

---

## LandSlope: Slope of property

       Gtl	Gentle slope
       Mod	Moderate Slope	
       Sev	Severe Slope

The slope of the land can affect the house price in several ways. Here are some possible impacts for each category:

- Gentle slope (Gtl): This is the most desirable slope for most homebuyers. It allows for easy landscaping and does not
  pose any significant challenges for building or maintaining a house. As a result, houses on gently sloping land may
  command higher prices than those on steeper terrain.
- Moderate slope (Mod): A moderate slope may still be desirable for some homebuyers, but it can present some challenges.
  For example, building a foundation on a sloping lot can be more expensive than on a level lot. Additionally,
  maintaining a sloping yard can be more difficult than a level one. Houses on moderate slopes may be priced lower than
  those on gentle slopes, but still higher than those on severe slopes.
- Severe slope (Sev): A severe slope can present significant challenges for building and maintaining a house. For
  example, building a foundation on a steep slope may require significant excavation or retaining walls, which can be
  expensive. In addition, maintaining a steeply sloping yard may require more effort and expense than a flatter yard. As
  a result, houses on severe slopes may be priced lower than those on more level land, and may be less desirable to some
  homebuyers. However, some homebuyers may appreciate the unique character and views that can come with a steeply
  sloping lot, and may be willing to pay a premium for it.

---

## Neighborhood: Physical locations within Ames city limits

       Blmngtn	Bloomington Heights
       Blueste	Bluestem
       BrDale	Briardale
       BrkSide	Brookside
       ClearCr	Clear Creek
       CollgCr	College Creek
       Crawfor	Crawford
       Edwards	Edwards
       Gilbert	Gilbert
       IDOTRR	Iowa DOT and Rail Road
       MeadowV	Meadow Village
       Mitchel	Mitchell
       Names	North Ames
       NoRidge	Northridge
       NPkVill	Northpark Villa
       NridgHt	Northridge Heights
       NWAmes	Northwest Ames
       OldTown	Old Town
       SWISU	South & West of Iowa State University
       Sawyer	Sawyer
       SawyerW	Sawyer West
       Somerst	Somerset
       StoneBr	Stone Brook
       Timber	Timberland
       Veenker	Veenker

The neighborhood in which a property is located can have a significant impact on its value. Here's a brief explanation
of each neighborhood in the Ames dataset and how they may impact house prices:

- Blmngtn (Bloomington Heights): This is a newer development on the west side of Ames with larger, more modern homes.
  Homes in this area may be more expensive due to their size and features.
- Blueste (Bluestem): This is a small development of mostly older, smaller homes. Homes in this area may be more
  affordable due to their age and size.
- BrDale (Briardale): This is a small neighborhood with mostly mid-sized homes on the south side of Ames. Homes in this
  area may be more affordable due to their location and size.
- BrkSide (Brookside): This is an older neighborhood with mostly smaller homes. Homes in this area may be more
  affordable due to their age and size.
- ClearCr (Clear Creek): This is a newer development with mostly mid-sized homes on the southeast side of Ames. Homes in
  this area may be more expensive due to their location and modern features.
- CollgCr (College Creek): This is a larger development on the west side of Ames with a mix of larger, newer homes and
  older homes. Homes in this area may vary in price depending on their age and features.
- Crawfor (Crawford): This is an older neighborhood with mostly mid-sized homes. Homes in this area may be more
  affordable due to their age and size.
- Edwards: This is a small neighborhood with mostly mid-sized homes on the east side of Ames. Homes in this area may be
  more affordable due to their location and size.
- Gilbert: This is a small town just north of Ames. Homes in this area may be more affordable than those in Ames due to
  their location and size.
- IDOTRR (Iowa DOT and Rail Road): This neighborhood is located near the railroad tracks and may be more affordable due
  to noise pollution and location.
- MeadowV (Meadow Village): This is a small development with mostly smaller, older homes. Homes in this area may be more
  affordable due to their age and size.
- Mitchel (Mitchell): This is an older neighborhood with mostly smaller homes. Homes in this area may be more affordable
  due to their age and size.
- Names (North Ames): This is a large neighborhood on the north side of Ames with a mix of newer and older homes. Homes
  in this area may vary in price depending on their age and features.
- NoRidge (Northridge): This is a large, upscale development on the north side of Ames with larger, newer homes. Homes
  in this area may be more expensive due to their size and modern features.
- NPkVill (Northpark Villa): This is a small development of mostly mid-sized homes on the northwest side of Ames. Homes
  in this area may be more affordable due to their location and size.
- NridgHt (Northridge Heights): This is a large, upscale development on the north side of Ames with larger, newer homes.
  Homes in this area may be more expensive due to their size and modern features.
- NWAmes (Northwest Ames): This is a large neighborhood on the northwest side of Ames with a mix of newer and older
  homes. Homes in this area may vary in price depending on their age and features.
- OldTown (Old Town): This is an older neighborhood near downtown Ames with mostly smaller homes. Homes in this area may
  be more affordable due to their age and size.
- SWISU (South & West of Iowa State University): This neighborhood is located near the Iowa State University campus and
  may be more expensive due to its proximity to the university and

---

## Condition1: Proximity to various conditions

       Artery	Adjacent to arterial street
       Feedr	Adjacent to feeder street	
       Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
       PosN	Near positive off-site feature--park, greenbelt, etc.
       PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad

The "Condition1" feature describes the proximity of the property to various conditions that may affect the house price.
Here's a more detailed explanation of each category:

- Artery: A property adjacent to an arterial street may experience high traffic volume and noise pollution, which can
  negatively impact its value.
- Feedr: A property adjacent to a feeder street may experience moderate traffic volume and noise pollution, which may
  slightly impact its value.
- Norm: A property in a normal location with no unusual proximity to any major features.
- RRNn: A property within 200 feet of a North-South railroad may experience noise pollution from train traffic, which
  may negatively impact its value.
- RRAn: A property adjacent to a North-South railroad may experience more significant noise pollution and vibration from
  train traffic, which can have a larger negative impact on its value.
- PosN: A property near a positive off-site feature such as a park or greenbelt may experience a more desirable
  location, which can increase its value.
- PosA: A property adjacent to a positive off-site feature may experience an even more desirable location, which can
  further increase its value.
- RRNe: A property within 200 feet of an East-West railroad may experience noise pollution from train traffic, which may
  negatively impact its value.
- RRAe: A property adjacent to an East-West railroad may experience more significant noise pollution and vibration from
  train traffic, which can have a larger negative impact on its value.

Overall, the proximity to arterial streets and railroads may negatively impact the value of the property due to noise
pollution and potential safety concerns, while the proximity to positive off-site features such as parks and greenbelts
may positively impact the value. The "Norm" category indicates a relatively neutral location with no unusual proximity
to any major features.

## Condition2: Proximity to various conditions (if more than one is present)

       Artery	Adjacent to arterial street
       Feedr	Adjacent to feeder street	
       Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
       PosN	Near positive off-site feature--park, greenbelt, etc.
       PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad

---

## BldgType: Type of dwelling

       1Fam	Single-family Detached	
       2FmCon	Two-family Conversion; originally built as one-family dwelling
       Duplx	Duplex
       TwnhsE	Townhouse End Unit
       TwnhsI	Townhouse Inside Unit

The type of dwelling, as represented by the BldgType feature, can have an impact on the house price in several ways.

- Single-family Detached (1Fam): These are standalone houses that do not share any walls or roofs with adjacent
  buildings. They typically offer more privacy and space than other types of dwellings, which can make them more
  desirable for families. This may result in a higher sale price compared to other types of dwellings.
- Two-family Conversion (2FmCon): These are houses that were originally built as single-family homes but have been
  converted into two separate units. This can be appealing for buyers who are looking for a property with rental income
  potential, or for multi-generational families who want to live together but still maintain some independence. The sale
  price may be influenced by the potential rental income or the cost of converting the property back to a single-family
  home.
- Duplex (Duplx): These are houses that are designed for two separate households and may share a common wall. Like the
  two-family conversion, duplexes can be appealing for buyers looking for rental income or multi-generational living.
  However, the shared wall may be less appealing to some buyers, which could result in a lower sale price compared to
  single-family detached homes.
- Townhouse End Unit (TwnhsE) and Townhouse Inside Unit (TwnhsI): These are houses that are typically part of a larger
  complex and share one or more walls with adjacent units. Townhouses can offer more affordable housing options than
  single-family homes and may also come with amenities like shared outdoor spaces or swimming pools. However, the shared
  walls and potential for noise from neighbors may make these properties less desirable to some buyers, which could
  affect the sale price. End units may be more desirable due to their increased privacy and natural light, which could
  result in a higher sale price compared to inside units.

---

## HouseStyle: Style of dwelling

       1Story	One story
       1.5Fin	One and one-half story: 2nd level finished
       1.5Unf	One and one-half story: 2nd level unfinished
       2Story	Two story
       2.5Fin	Two and one-half story: 2nd level finished
       2.5Unf	Two and one-half story: 2nd level unfinished
       SFoyer	Split Foyer
       SLvl	Split Level

---

## OverallQual: Rates the overall material and finish of the house

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average
       5	Average
       4	Below Average
       3	Fair
       2	Poor
       1	Very Poor

---

## OverallCond: Rates the overall condition of the house

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average	
       5	Average
       4	Below Average	
       3	Fair
       2	Poor
       1	Very Poor

---

## YearBuilt: Original construction date

---

## YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)

---

## RoofStyle: Type of roof

       Flat	Flat
       Gable	Gable
       Gambrel	Gabrel (Barn)
       Hip	Hip
       Mansard	Mansard
       Shed	Shed

The type of roof can have an impact on a home's value and appeal to buyers. Here's a brief explanation of each roof
style:

- Flat: Flat roofs have little to no pitch and are typically found on modern or contemporary homes. They can provide
  extra outdoor space for a rooftop deck or garden. However, flat roofs may require more maintenance and repairs than
  other roof types.
- Gable: Gable roofs are the most common roof type and are easily recognizable by their triangular shape. They are
  popular because they are easy to build and provide good ventilation. Gable roofs are also more resistant to strong
  winds and heavy snow loads.
- Gambrel: Gambrel roofs are often referred to as barn-style roofs and have two distinct slopes on each side. They
  provide extra space for an attic or living area and are often used on colonial or Dutch-style homes.
- Hip: Hip roofs have slopes on all four sides and are more stable than gable roofs. They provide good protection
  against strong winds and heavy snow loads. Hip roofs are popular on ranch-style and Mediterranean-style homes.
- Mansard: Mansard roofs have two slopes on all four sides and are often used on French or Victorian-style homes. They
  provide extra living space in the attic and can add a unique architectural feature to a home.
- Shed: Shed roofs have a single slope and are often used on modern or contemporary homes. They are simple and easy to
  construct but may not provide as much protection against the elements as other roof types.

The impact of roof style on a home's value will depend on a number of factors, including the local real estate market
and the preferences of potential buyers. However, some buyers may be willing to pay a premium for a home with a unique
or high-quality roof. In general, well-maintained roofs that are in good condition and offer protection against the
elements are likely to be viewed positively by potential buyers.

---

## RoofMatl: Roof material

       ClyTile	Clay or Tile
       CompShg	Standard (Composite) Shingle
       Membran	Membrane
       Metal	Metal
       Roll	Roll
       Tar&Grv	Gravel & Tar
       WdShake	Wood Shakes
       WdShngl	Wood Shingles

The choice of roofing material can affect the aesthetic appeal, durability, and maintenance requirements of a property,
which may in turn impact its market value. Here are some potential impacts of the different types of roofing materials:

- Clay or Tile (ClyTile): Clay or tile roofing can be a durable and long-lasting option, with an expected lifespan of 50
  years or more. These materials can also provide good insulation and fire resistance. However, they tend to be more
  expensive than other roofing materials, and their weight may require additional structural support.
- Standard (Composite) Shingle (CompShg): Composite shingles are a popular and relatively affordable roofing material,
  with an expected lifespan of around 20-30 years. They come in a range of colors and styles, and can be made to mimic
  the look of more expensive materials like wood or slate. However, they may not be as durable as some other options,
  and may be prone to damage from severe weather.
- Membrane (Membran): Membrane roofing is typically used on flat or low-sloped roofs, and consists of a single-ply sheet
  of material like PVC or TPO. This type of roofing can be lightweight, easy to install, and resistant to UV rays and
  water damage. However, it may not be as visually appealing as other options, and may require more maintenance over
  time.
- Metal (Metal): Metal roofing can be a durable and energy-efficient option, with an expected lifespan of 40-70 years.
  It can also be made from a variety of materials like aluminum, steel, or copper, and can be painted or coated to match
  the style of the home. However, metal roofing may be more expensive than other materials, and can be prone to denting
  or noise from rain or hail.
- Roll (Roll): Roll roofing is a relatively inexpensive and easy-to-install option, typically used on low-sloped or flat
  roofs. However, it may not be as durable as other options and may require more frequent maintenance.
- Gravel & Tar (Tar&Grv): Gravel and tar roofing is a type of built-up roofing (BUR) that consists of layers of asphalt
  or tar paper, topped with a layer of gravel for protection. This type of roofing can be durable and fire-resistant,
  but may be more prone to leaks and may require periodic maintenance.
- Wood Shakes (WdShake) and Wood Shingles (WdShngl): Wood roofing can provide a natural and rustic look, and can be made
  from a variety of wood types like cedar or redwood. However, it may require more maintenance than other options, and
  can be susceptible to rot or insect damage. Wood roofing may also be more expensive than other materials.

---

## Exterior1st: Exterior covering on house

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast	
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles

## Exterior2nd: Exterior covering on house (if more than one material)

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles

The exterior covering on a house can have a significant impact on its appearance and therefore, its value. Here's a
brief explanation of each category and how it may impact the house price:

- AsbShng (Asbestos Shingles): This type of shingle was commonly used in the mid-20th century, but has since been
  largely replaced due to health concerns associated with asbestos. Homes with this type of siding may be seen as
  outdated and may have a negative impact on the house price.
- AsphShn (Asphalt Shingles): Asphalt shingles are a popular and relatively inexpensive choice for roofing. They are
  available in a variety of colors and can be a neutral option that doesn't add or detract from the house's value.
- BrkComm (Brick Common): This refers to a common type of brick that is typically used for structural purposes rather
  than decorative. Brick is a durable and low-maintenance option that can add value to a home.
- BrkFace (Brick Face): This refers to a type of brick that is used for decorative purposes rather than structural.
  Brick is a popular and timeless option that can add value to a home.
- CBlock (Cinder Block): Cinder block is a common building material used for foundations and retaining walls. It is a
  durable and low-maintenance option, but may not add much value to a home.
- CemntBd (Cement Board): Cement board is a relatively new type of exterior siding made from cement and wood fibers. It
  is durable and low-maintenance, and may add value to a home.
- HdBoard (Hard Board): Hard board siding is a type of engineered wood that is durable and low-maintenance. It is
  available in a variety of styles and finishes, and may add value to a home.
- ImStucc (Imitation Stucco): Imitation stucco, also known as EIFS (Exterior Insulation and Finish System), is a
  synthetic material that is designed to look like traditional stucco. It is a relatively new option that may not be as
  durable as other types of siding.
- MetalSd (Metal Siding): Metal siding is a durable and low-maintenance option that can add value to a home. It is
  available in a variety of styles and finishes.
- Other: This category may include a variety of non-standard siding options that could have a wide range of impacts on
  the house price.
- Plywood: Plywood siding is a low-cost option that may not add much value to a home. It is generally not as durable as
  other types of siding.
- PreCast (PreCast): Precast concrete panels are a durable and low-maintenance option that can add value to a home.
- Stone: Stone siding is a high-end option that can add significant value to a home. It is durable and low-maintenance,
  but also expensive.
- Stucco: Traditional stucco is a popular and durable option that can add value to a home. It is available in a variety
  of colors and textures.
- VinylSd (Vinyl Siding): Vinyl siding is a popular and low-cost option that can add value to a home. It is available in
  a variety of styles and colors.
- Wd Sdng (Wood Siding): Wood siding is a classic and timeless option that can add value to a home. It is available in a
  variety of styles and finishes.
- WdShing (Wood Shingles): Wood shingles are a high-end option that can add significant value to a home. They are
  durable and low-maintenance, but also expensive.

---

## MasVnrType: Masonry veneer type

       BrkCmn	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       None	None
       Stone	Stone

The type of masonry veneer on a house can impact the house price due to a number of factors.

- BrkCmn (Brick Common): This type of veneer is made of small, irregularly-shaped pieces of brick that are typically
  used for low-cost construction. Houses with this type of veneer may be considered less valuable due to the perception
  that it is a cheaper material.
- BrkFace (Brick Face): This type of veneer is made of thin, flat pieces of brick that are attached to the exterior of
  the house. Brick is a popular material for home construction due to its durability and visual appeal, and houses with
  this type of veneer may be more valuable.
- CBlock (Cinder Block): Cinder blocks are a type of concrete block that is made of cement, sand, and water, and are
  used for building foundations and walls. Houses with cinder block veneer may be considered less valuable than those
  with other types of veneer due to its appearance and durability.
- None: Houses without masonry veneer may be considered less valuable than those with veneer due to the perception that
  it is a less visually appealing and durable material.
- Stone: This type of veneer is made of natural stone and is a premium material. Houses with stone veneer may be
  considered more valuable due to the perception of high-quality and durability.

## MasVnrArea: Masonry veneer area in square feet

---

## ExterQual: Evaluates the quality of the material on the exterior

       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor

---

## ExterCond: Evaluates the present condition of the material on the exterior

       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor

---

## Foundation: Type of foundation

       BrkTil	Brick & Tile
       CBlock	Cinder Block
       PConc	Poured Contrete	
       Slab	Slab
       Stone	Stone
       Wood	Wood

- BrkTil (Brick & Tile): This type of foundation is considered to be quite sturdy and durable, which can be attractive
  to home buyers. Additionally, it may provide better insulation and protection against moisture and pests, which could
  be beneficial in certain climates. These factors could potentially lead to a higher house price.
- CBlock (Cinder Block): Cinder block foundations are typically less expensive to build than other types of foundations,
  but they may be less durable and less resistant to water damage. This could potentially make the house less attractive
  to buyers, which could result in a lower price.
- PConc (Poured Concrete): Poured concrete foundations are typically more expensive to build than cinder block
  foundations, but they are also generally considered to be more durable and better at resisting water damage. This
  could make the house more attractive to buyers and potentially lead to a higher price.
- Slab: A slab foundation is a concrete pad poured directly onto the ground. This type of foundation is typically less
  expensive to build than other types, but it may not be as durable and may be more prone to cracking. It could also
  limit the ability to add a basement or additional space below the house. These factors could make the house less
  attractive to buyers, which could potentially result in a lower price.
- Stone: Stone foundations were common in older homes and may be considered to be more aesthetically pleasing by some
  buyers. However, they may also be less durable and less resistant to water damage than other types of foundations.
  This could potentially make the house less attractive to buyers and result in a lower price.
- Wood: Wood foundations are not very common, but they may be used in certain areas where there is a lot of moisture or
  soil instability. However, they may be more prone to rot and damage from pests, which could make the house less
  attractive to buyers and result in a lower price.

---

## BsmtQual: Evaluates the height of the basement

       Ex	Excellent (100+ inches)	
       Gd	Good (90-99 inches)
       TA	Typical (80-89 inches)
       Fa	Fair (70-79 inches)
       Po	Poor (<70 inches
       NA	No Basement

---

## BsmtCond: Evaluates the general condition of the basement

       Ex	Excellent
       Gd	Good
       TA	Typical - slight dampness allowed
       Fa	Fair - dampness or some cracking or settling
       Po	Poor - Severe cracking, settling, or wetness
       NA	No Basement

---

## BsmtExposure: Refers to walkout or garden level walls

       Gd	Good Exposure
       Av	Average Exposure (split levels or foyers typically score average or above)	
       Mn	Mimimum Exposure
       No	No Exposure
       NA	No Basement

---

## BsmtFinType1: Rating of basement finished area

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement

---

## BsmtFinSF1: Type 1 finished square feet

---

## BsmtFinType2: Rating of basement finished area (if multiple types)

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement

---

## BsmtFinSF2: Type 2 finished square feet

---

## BsmtUnfSF: Unfinished square feet of basement area

---

## TotalBsmtSF: Total square feet of basement area

---

## Heating: Type of heating

       Floor	Floor Furnace
       GasA	Gas forced warm air furnace
       GasW	Gas hot water or steam heat
       Grav	Gravity furnace	
       OthW	Hot water or steam heat other than gas
       Wall	Wall furnace

- Floor Furnace: This is a type of heating system that is installed beneath the floor of a room. It can be an efficient
  way to heat a space, but it may be less common in modern homes. A floor furnace may not have a significant impact on
  the house price.
- Gas Forced Warm Air Furnace (GasA): This is a common type of heating system that uses natural gas to heat air, which
  is then circulated through the house via ducts. Gas forced warm air furnaces are generally efficient and reliable, and
  may be preferred by homebuyers. A house with a GasA heating system may have a slightly higher price compared to a
  house with a less efficient heating system.
- Gas Hot Water or Steam Heat (GasW): This type of heating system uses natural gas to heat water or steam, which is then
  circulated through radiators or baseboard heaters to warm the home. Gas hot water or steam heat can be an efficient
  and effective way to heat a home, but it may be less common in newer homes. A GasW heating system may not have a
  significant impact on the house price.
- Gravity Furnace (Grav): This is an older type of heating system that relies on the natural circulation of hot air to
  warm a home. Gravity furnaces are less common in modern homes, and may not be as efficient as other types of heating
  systems. A house with a Gravity furnace may have a slightly lower price compared to a house with a more modern and
  efficient heating system.
- Hot Water or Steam Heat Other than Gas (OthW): This type of heating system uses a fuel source other than natural gas (
  such as oil or electricity) to heat water or steam, which is then circulated through radiators or baseboard heaters to
  warm the home. Hot water or steam heat other than gas may be less common in modern homes, and may be more expensive to
  operate. A house with an OthW heating system may have a slightly lower price compared to a house with a more efficient
  heating system.
- Wall Furnace (Wall): This is a type of heating system that is mounted on the wall and uses natural gas or propane to
  heat air, which is then circulated through the room. Wall furnaces are generally less common in modern homes, and may
  not be as efficient as other types of heating systems. A house with a Wall furnace may have a slightly lower price
  compared to a house with a more modern and efficient heating system.

---

## HeatingQC: Heating quality and condition

       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor

---

## CentralAir: Central air conditioning

       N	No
       Y	Yes

- N (No): If a house doesn't have central air conditioning, it can be less desirable to potential buyers, especially in
  areas with hot summers. Without central AC, residents may have to rely on window units or other cooling methods, which
  can be less efficient and more expensive. As a result, houses without central AC may have lower resale values compared
  to similar houses with central AC.
- Y (Yes): Homes with central air conditioning are generally more desirable to potential buyers, as it provides more
  consistent cooling throughout the house and can be more energy-efficient. Houses with central AC may have higher
  resale values than similar houses without it.

---

## Electrical: Electrical system

       SBrkr	Standard Circuit Breakers & Romex
       FuseA	Fuse Box over 60 AMP and all Romex wiring (Average)	
       FuseF	60 AMP Fuse Box and mostly Romex wiring (Fair)
       FuseP	60 AMP Fuse Box and mostly knob & tube wiring (poor)
       Mix	Mixed

---

## 1stFlrSF: First Floor square feet

## 2ndFlrSF: Second floor square feet

---

## LowQualFinSF: Low quality finished square feet (all floors)

---

## GrLivArea: Above grade (ground) living area square feet

---

## BsmtFullBath: Basement full bathrooms

---

## BsmtHalfBath: Basement half bathrooms

---

## FullBath: Full bathrooms above grade

---

## HalfBath: Half baths above grade

---

## Bedroom: Bedrooms above grade (does NOT include basement bedrooms)

---

## KitchenAbvGr: Kitchens above grade

---

## KitchenQual: Kitchen quality

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor

---

## TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)

---

## Functional: Home functionality (Assume typical unless deductions are warranted)

       Typ	Typical Functionality
       Min1	Minor Deductions 1
       Min2	Minor Deductions 2
       Mod	Moderate Deductions
       Maj1	Major Deductions 1
       Maj2	Major Deductions 2
       Sev	Severely Damaged
       Sal	Salvage only

The "Functional" feature describes the overall functionality of the house. Here's how each category might impact the
house price:

- Typ (Typical Functionality): This category indicates that the house is functioning as it should be and all systems are
  in good condition. This is the most desirable category and would likely have little to no impact on the house price.
- Min1 (Minor Deductions 1): This category indicates that the house has some minor issues that may require repairs or
  upgrades, such as a faulty appliance or outdated fixtures. This could lead to a slight decrease in the house price.
- Min2 (Minor Deductions 2): This category indicates that the house has more significant issues than Min1, such as an
  outdated electrical system or plumbing issues. This could lead to a greater decrease in the house price.
- Mod (Moderate Deductions): This category indicates that the house has moderate functional issues, such as a damaged
  roof or foundation problems. This would likely result in a significant decrease in the house price.
- Maj1 (Major Deductions 1): This category indicates that the house has major functional issues that would require
  significant repairs or upgrades, such as a leaking roof or a malfunctioning HVAC system. This could lead to a
  substantial decrease in the house price.
- Maj2 (Major Deductions 2): This category indicates that the house has even more severe functional issues than Maj1,
  such as serious structural damage or significant water damage. This would likely result in a significant decrease in
  the house price.
- Sev (Severely Damaged): This category indicates that the house is severely damaged and requires significant repairs to
  be habitable. The house would likely have a very low value and would be difficult to sell.
- Sal (Salvage only): This category indicates that the house is beyond repair and should be demolished. The house would
  have no value and would likely need to be sold for the value of the land only.

---

## Fireplaces: Number of fireplaces

---

## FireplaceQu: Fireplace quality

       Ex	Excellent - Exceptional Masonry Fireplace
       Gd	Good - Masonry Fireplace in main level
       TA	Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
       Fa	Fair - Prefabricated Fireplace in basement
       Po	Poor - Ben Franklin Stove
       NA	No Fireplace

---

## GarageType: Garage location

       2Types	More than one type of garage
       Attchd	Attached to home
       Basment	Basement Garage
       BuiltIn	Built-In (Garage part of house - typically has room above garage)
       CarPort	Car Port
       Detchd	Detached from home
       NA	No Garage

The GarageType feature describes the location of the garage in the property. Here is a brief explanation of each
category:

- 2Types: More than one type of garage. This indicates that the property has multiple garages, which could be a
  desirable feature for a buyer with multiple vehicles or a need for additional storage space.
- Attchd: Attached to home. This means that the garage is physically attached to the main structure of the house. This
  could be seen as a positive feature as it provides convenient and easy access to the house, especially during bad
  weather.
- Basment: Basement Garage. This indicates that the garage is located in the basement of the property. This may be less
  desirable than an attached or detached garage, as it could require more effort to access and could be prone to
  moisture or drainage issues.
- BuiltIn: Built-In (Garage part of house - typically has room above garage). This means that the garage is built into
  the structure of the house and may have living space above it. This could be seen as a positive feature, as it could
  provide additional living space or storage options.
- CarPort: Car Port. This indicates that the property has a sheltered area for a car, but it is not fully enclosed like
  a traditional garage. This may be seen as a less desirable feature as it provides less security and protection for a
  vehicle.
- Detchd: Detached from home. This means that the garage is physically separated from the main structure of the house.
  This could be seen as a positive feature as it provides additional privacy and could reduce noise levels inside the
  house. However, it may be less convenient to access the house, especially during bad weather.
- NA: No Garage. This indicates that the property does not have a garage. This may be seen as a negative feature, as it
  provides less security and protection for a vehicle, and may be less attractive to buyers who prioritize having a
  garage.

Overall, the GarageType feature can have an impact on the house price depending on the buyer's preferences and needs.
For example, a property with an attached garage may be more desirable for a buyer who values convenience and easy access
to the house, while a property with a detached garage may be more attractive to a buyer who prioritizes privacy and
reduced noise levels.

---

## GarageYrBlt: Year garage was built

The year the garage was built can have a significant impact on the house price because it indicates the age and
condition of the garage. A newer garage may be in better condition and offer more features than an older one, such as
better insulation or modern electrical wiring, which could increase the value of the property.

On the other hand, an old garage may require maintenance or repair, which could decrease the value of the property.
Additionally, if the garage was built in a style that does not match the architectural style of the house or the overall
neighborhood, it may not add value to the property.

In summary, the impact of the garage year built on the house price depends on various factors such as the condition,
features, style, and age of the garage, as well as the preferences and expectations of buyers in the local real estate
market.

---

## GarageFinish: Interior finish of the garage

       Fin	Finished
       RFn	Rough Finished	
       Unf	Unfinished
       NA	No Garage

The interior finish of a garage can have an impact on the overall value of a house. A finished garage can provide
additional living space or storage, which may be desirable for some buyers. A rough-finished garage may not be as
appealing, but could still provide functional space. An unfinished garage may be viewed as a project or potential space
for improvement by some buyers.

A garage that is not finished, or one that has a low-quality finish, may be less attractive to potential buyers, which
could result in a lower sale price. On the other hand, a garage that is well finished and well-maintained may be viewed
as an attractive feature that adds value to the home.

Therefore, the value of a garage with a particular interior finish may vary depending on the buyer's preferences and the
overall condition and quality of the garage.

---

## GarageCars: Size of garage in car capacity

---

## GarageArea: Size of garage in square feet

---

## GarageQual: Garage quality

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       NA	No Garage

---

## GarageCond: Garage condition

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       NA	No Garage

---

## PavedDrive: Paved driveway

       Y	Paved 
       P	Partial Pavement
       N	Dirt/Gravel

- Paved driveways are typically considered a desirable feature since they provide a smooth surface for driving and
  parking. A house with a paved driveway may be more attractive to buyers, particularly those who value convenience and
  ease of use.
- Partial pavement may have a mixed impact on house price. On the one hand, it may suggest that the property is older or
  in need of some repair. On the other hand, it could also indicate that the homeowner has taken steps to upgrade the
  property without completely redoing the driveway.
- A dirt or gravel driveway may suggest that the property is more rural or rustic in nature. Depending on the buyer's
  preferences, this could be seen as either a positive or negative feature. However, it may be viewed as a negative
  feature if the buyer values a more polished or upscale appearance.

---

## WoodDeckSF: Wood deck area in square feet

---

## OpenPorchSF: Open porch area in square feet

---

## EnclosedPorch: Enclosed porch area in square feet

---

## 3SsnPorch: Three season porch area in square feet

---

## ScreenPorch: Screen porch area in square feet

---

## PoolArea: Pool area in square feet

---

## PoolQC: Pool quality

       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       NA	No Pool

---

## Fence: Fence quality

       GdPrv	Good Privacy
       MnPrv	Minimum Privacy
       GdWo	Good Wood
       MnWw	Minimum Wood/Wire
       NA	No Fence

---

## MiscFeature: Miscellaneous feature not covered in other categories

       Elev	Elevator
       Gar2	2nd Garage (if not described in garage section)
       Othr	Other
       Shed	Shed (over 100 SF)
       TenC	Tennis Court
       NA	None

- Elevator (Elev): If the house has an elevator, it can be a significant feature for people with mobility issues or
  those who prefer the convenience of having an elevator. This feature may add value to the house.
- 2nd Garage (Gar2): If the house has a second garage, it can provide additional storage space or parking for an extra
  vehicle. This feature may add value to the house.
- Other (Othr): This category may include features such as greenhouses, guesthouses, or other unique features that are
  not commonly found in homes. The impact on house price would depend on the specific feature and its desirability to
  potential buyers.
- Shed (Shed): If the house has a shed, it can provide additional storage space or workspace. The impact on house price
  would depend on the size and condition of the shed.
- Tennis Court (TenC): If the house has a tennis court, it can be a significant feature for people who enjoy playing
  tennis or other outdoor sports. However, not all buyers may be interested in a tennis court, so the impact on house
  price may vary.
- None (NA): If the house doesn't have any miscellaneous features, it may not have a significant impact on the house
  price. However, the absence of certain features that are commonly found in homes (such as a garage) may have a
  negative impact on the house price.

## MiscVal: $Value of miscellaneous feature

---

## MoSold: Month Sold (MM)

## YrSold: Year Sold (YYYY)

The month and year in which a house is sold can potentially impact its price due to a variety of factors such as
seasonal demand, economic conditions, and market trends.

For example, in many parts of the world, the housing market tends to be more active in the spring and summer months,
which can lead to higher prices due to increased demand. On the other hand, the market may be slower during the winter
months, which could result in lower prices due to decreased demand.

Similarly, economic conditions such as interest rates, unemployment rates, and overall economic growth can affect the
housing market and impact prices. For example, during a recession, the housing market may experience a downturn with
decreased demand and lower prices. In contrast, during times of economic growth, demand for housing may increase,
leading to higher prices.

Finally, market trends can also impact the price of a house. For example, if there is a trend towards smaller homes or
eco-friendly homes, houses that fit those criteria may sell for a higher price than larger or less eco-friendly homes.
Overall, while the month and year in which a house is sold may not be the most important factor in determining its
price, it can certainly play a role in shaping the market and influencing prices.

---

## SaleType: Type of sale

       WD 	Warranty Deed - Conventional
       CWD	Warranty Deed - Cash
       VWD	Warranty Deed - VA Loan
       New	Home just constructed and sold
       COD	Court Officer Deed/Estate
       Con	Contract 15% Down payment regular terms
       ConLw	Contract Low Down payment and low interest
       ConLI	Contract Low Interest
       ConLD	Contract Low Down
       Oth	Other

---

## SaleCondition: Condition of sale

       Normal	Normal Sale
       Abnorml	Abnormal Sale -  trade, foreclosure, short sale
       AdjLand	Adjoining Land Purchase
       Alloca	Allocation - two linked properties with separate deeds, typically condo with a garage unit	
       Family	Sale between family members
       Partial	Home was not completed when last assessed (associated with New Homes)
