**Numerical Columns:**

- `order` : Observation Number. (Discrete)
- `pid` : Parcel identification number - can be used with city web site for parcel review. (Nominal)
- `ms_subclass` : Identifies the type of dwelling involved in the sale. (Nominal) **It's a categorical value**
- `lot_frontage`: Linear feet of street connected to property. (Continuous)
- `lot_area`: Lot size in square feet.(Continuous)
- `overall_qual`: Overall material and finish quality. (Ordinal)
- `overall_cond`: Overall condition rating. (Ordinal)
- `year_built`: Original construction date. (Discrete)
- `year_remod/add`: Remodel date (same as construction date if no remodeling or additions). (Discrete)
- `mas_vnr_area`: Masonry veneer area in square feet. (Continuous)
- `bsmtfin_sf_1`: Type 1 finished square feet. (Continuous)
- `bsmtfin_sf_2`: Type 2 finished square feet. (Continuous)
- `bsmt_unf_sf`: Unfinished square feet of basement area. (Continuous)
- `total_bsmt_sf`: Total square feet of basement area. (Continuous)
- `1st_flr_sf`: First Floor square feet. (Continuous)
- `2nd_flr_sf`: Second floor square feet. (Continuous)
- `low_qual_fin_sf`: Low quality finished square feet (all floors). (Continuous)
- `gr_liv_area`: Above-grade (ground) living area square feet. (Continuous)
- `bsmt_full_bath`: Basement full bathrooms. (Discrete)
- `bsmt_half_bath`: Basement half bathrooms. (Discrete)
- `full_bath`: Full bathrooms above grade. (Discrete)
- `half_bath`: Half baths above grade. (Discrete)
- `bedroom_abvgr`: Bedrooms above grade (does NOT include basement bedrooms). (Discrete)
- `kitchen_abvgr`: Kitchens above grade. (Discrete)
- `totrms_abvgrd`: Total rooms above grade (does not include bathrooms). (Discrete)
- `fireplaces`: Number of fireplaces. (Discrete)
- `garage_yr_blt` : Year garage was built. (Discrete)
- `garage_cars`: Size of garage in car capacity. (Discrete)
- `garage_area`: Size of garage in square feet. (Continuous)
- `wood_deck_sf`: Wood deck area in square feet. (Continuous)
- `open_porch_sf`: Open porch area in square feet. (Continuous)
- `enclosed_porch`: Enclosed porch area in square feet. (Continuous)
- `3ssn_porch`: Three season porch area in square feet. (Continuous)
- `screen_porch`: Screen porch area in square feet. (Continuous)
- `pool_area`: Pool area in square feet. (Continuous)
- `misc_val`: Value of miscellaneous feature. (Continuous)
- `mo_sold` : Month Sold (MM). (Discrete)
- `yr_sold` : Year Sold (YYYY). (Discrete)
- `saleprice` : Sale price $$. (Continuous)



**Object Columns**

- `ms_zoning` : Zoning classification. (Nominal)
   | Value | Description                       |
|------|-----------------------------------|
| A(all)    | Agriculture                       |
| C(all)    | Commercial                        |
| FV   | Floating Village Residential      |
| I(all)    | Industrial                        |
| RH   | Residential High Density          |
| RL   | Residential Low Density           |
| RP   | Residential Low Density Park      |
| RM   | Residential Medium Density        |

- `street` : Type of road access to property. (Nominal)
| Value| Description |
|------|-------------|
| Grvl | Gravel      |
| Pave | Paved       |

- `alley` : Type of alley access to property. (Nominal)
| Value| Description           |
|------|-----------------------|
| Grvl | Gravel                |
| Pave | Paved                 |
| nan  | No alley access       |


- `lot_shape` : General shape of property. (Ordinal)
| Value| Description            |
|------|------------------------|
| Reg  | Regular                |
| IR1  | Slightly irregular     |
| IR2  | Moderately Irregular   |
| IR3  | Irregular              |

- `land_contour` : Flatness of the property. (Nominal)
| Value| Description                                            |
|------|--------------------------------------------------------|
| Lvl  | Near Flat/Level                                        |
| Bnk  | Banked - Quick and significant rise from street grade to building |
| HLS  | Hillside - Significant slope from side to side         |
| Low  | Depression                                             |

- `utilities` : Types of Utilities available. (Ordinal)
| Value  | Description                                       |
|--------|---------------------------------------------------|
| AllPub | All public Utilities (E, G, W, & S)               |
| NoSewr | Electricity, Gas, and Water (Septic Tank)         |
| NoSeWa | Electricity and Gas Only                          |
| ELO    | Electricity only                                  |

  
- `lot_config` : Lot Configuration. (Nominal)
| Value   | Description                        |
|---------|------------------------------------|
| Inside  | Inside lot                         |
| Corner  | Corner lot                         |
| CulDSac | Cul-de-sac                         |
| FR2     | Frontage on 2 sides of property    |
| FR3     | Frontage on 3 sides of property    |


- `land_slope` : Slope of the Property. (Ordinal)
| Value| Description      |
|------|------------------|
| Gtl  | Gentle slope     |
| Mod  | Moderate Slope   |
| Sev  | Severe Slope     |


- `neighborhood` : Physical locations within Ames city limits (map available). (Nominal)
| Value    | Description                                      |
|----------|--------------------------------------------------|
| Blmngtn  | Bloomington Heights                              |
| Blueste  | Bluestem                                         |
| BrDale   | Briardale                                        |
| BrkSide  | Brookside                                        |
| ClearCr  | Clear Creek                                      |
| CollgCr  | College Creek                                    |
| Crawfor  | Crawford                                         |
| Edwards  | Edwards                                          |
| Gilbert  | Gilbert                                          |
| Greens   | Greens                                           |
| GrnHill  | Green Hills                                      |
| IDOTRR   | Iowa DOT and Rail Road                           |
| Landmrk  | Landmark                                         |
| MeadowV  | Meadow Village                                   |
| Mitchel  | Mitchell                                         |
| NAmes    | North Ames                                       |
| NoRidge  | Northridge                                       |
| NPkVill  | Northpark Villa                                  |
| NridgHt  | Northridge Heights                               |
| NWAmes   | Northwest Ames                                   |
| OldTown  | Old Town                                         |
| SWISU    | South & West of Iowa State University            |
| Sawyer   | Sawyer                                           |
| SawyerW  | Sawyer West                                      |
| Somerst  | Somerset                                         |
| StoneBr  | Stone Brook                                      |
| Timber   | Timberland                                       |
| Veenker  | Veenker                                          |


- `condition_1` : Proximity to various conditions. (Nominal)
| Value| Description                                  |
|------|----------------------------------------------|
| Artery | Adjacent to arterial street                 |
| Feedr  | Adjacent to feeder street                   |
| Norm   | Normal                                       |
| RRNn   | Within 200' of North-South Railroad          |
| RRAn   | Adjacent to North-South Railroad             |
| PosN   | Near positive off-site feature--park, greenbelt, etc. |
| PosA   | Adjacent to positive off-site feature        |
| RRNe   | Within 200' of East-West Railroad            |
| RRAe   | Adjacent to East-West Railroad               |


- `condition_2` : Proximity to various conditions (if more than one is present). (Nominal)
| Value| Description                                  |
|------|----------------------------------------------|
| Artery | Adjacent to arterial street                 |
| Feedr  | Adjacent to feeder street                   |
| Norm   | Normal                                       |
| RRNn   | Within 200' of North-South Railroad          |
| RRAn   | Adjacent to North-South Railroad             |
| PosN   | Near positive off-site feature--park, greenbelt, etc. |
| PosA   | Adjacent to positive off-site feature        |
| RRAe   | Adjacent to East-West Railroad               |


- `bldg_type` : Type of dwelling. (Nominal)
| Value | Description                                             |
|-------|---------------------------------------------------------|
| 1Fam  | Single-family Detached                                  |
| 2fmCon| Two-family Conversion; originally built as one-family dwelling |
| Duplex | Duplex                                                  |
| TwnhsE| Townhouse End Unit                                      |
| Twnhs| Townhouse Inside Unit                                   |


- `house_style` : Style of dwelling. (Nominal)
| Value  | Description                                   |
|--------|-----------------------------------------------|
| 1Story | One story                                      |
| 1.5Fin | One and one-half story: 2nd level finished     |
| 1.5Unf | One and one-half story: 2nd level unfinished   |
| 2Story | Two story                                      |
| 2.5Fin | Two and one-half story: 2nd level finished     |
| 2.5Unf | Two and one-half story: 2nd level unfinished   |
| SFoyer | Split Foyer                                    |
| SLvl   | Split Level                                    |


- `roof_style` : Type of Roof. (Nominal)
| Value  | Description   |
|--------|---------------|
| Flat   | Flat          |
| Gable  | Gable         |
| Gambrel| Gabrel (Barn)  |
| Hip    | Hip           |
| Mansard| Mansard       |
| Shed   | Shed          |


- `roof_matl` : Roof material. (Nominal)
| Value   | Description                    |
|---------|--------------------------------|
| ClyTile | Clay or Tile                   |
| CompShg | Standard (Composite) Shingle   |
| Membran | Membrane                       |
| Metal   | Metal                          |
| Roll    | Roll                           |
| Tar&Grv | Gravel & Tar                   |
| WdShake | Wood Shakes                    |
| WdShngl | Wood Shingles                  |


- `exterior_1st` : Exterior covering in House. (Nominal)
| Value   | Description         |
|---------|---------------------|
| AsbShng | Asbestos Shingles   |
| AsphShn | Asphalt Shingles    |
| BrkComm | Brick Common        |
| BrkFace | Brick Face          |
| CBlock  | Cinder Block        |
| CemntBd | Cement Board        |
| HdBoard | Hard Board           |
| ImStucc | Imitation Stucco    |
| MetalSd | Metal Siding        |
| Plywood | Plywood             |
| PreCast | PreCast             |
| Stone   | Stone               |
| Stucco  | Stucco              |
| VinylSd | Vinyl Siding        |
| Wd Sdng | Wood Siding         |
| WdShing | Wood Shingles       |


- `exterior_2nd` : Exterior covering in House (If more than one material). (Nominal)
| Value   | Description         |
|---------|---------------------|
| AsbShng | Asbestos Shingles   |
| AsphShn | Asphalt Shingles    |
| BrkComm | Brick Common        |
| BrkFace | Brick Face          |
| CBlock  | Cinder Block        |
| CemntBd | Cement Board        |
| HdBoard | Hard Board           |
| ImStucc | Imitation Stucco    |
| MetalSd | Metal Siding        |
| Other   | Other               |
| Plywood | Plywood             |
| PreCast | PreCast             |
| Stone   | Stone               |
| Stucco  | Stucco              |
| VinylSd | Vinyl Siding        |
| Wd Sdng | Wood Siding         |
| WdShing | Wood Shingles       |
- `mas_vnr_type` : Masonry veneer type. (Nominal)
| Value   | Description    |
|---------|----------------|
| BrkCmn  | Brick Common   |
| BrkFace | Brick Face     |
| CBlock  | Cinder Block   |
| nan    | None           |
| Stone   | Stone          |


- `exter_qual` : Evaluates the quality of the material on the exterior. (Ordinal)
| Value| Description     |
|------|-----------------|
| Ex   | Excellent       |
| Gd   | Good            |
| TA   | Average/Typical |
| Fa   | Fair            |


- `exter_cond` : Evaluates the present condition of the material on the exterior. (Ordinal)
| Value| Description     |
|------|-----------------|
| Ex   | Excellent       |
| Gd   | Good            |
| TA   | Average/Typical |
| Fa   | Fair            |
| Po   | Poor            |

- `foundation` : Type of Foundation. (Nominal)
| Code   | Description      |
|--------|------------------|
| BrkTil | Brick & Tile     |
| CBlock | Cinder Block     |
| PConc  | Poured Concrete  |
| Slab   | Slab             |
| Stone  | Stone            |
| Wood   | Wood             |


- `bsmt_qual` : Evaluates the height of the basement. (Ordinal)
| Code | Description               |
|------|---------------------------|
| Ex   | Excellent (100+ inches)   |
| Gd   | Good (90-99 inches)       |
| TA   | Typical (80-89 inches)    |
| Fa   | Fair (70-79 inches)        |
| Po   | Poor (<70 inches)         |
| nan  | No Basement               |


- `bsmt_cond` : Evaluates the general condition of the basement. (Ordinal)
| Code | Description                                     |
|------|-------------------------------------------------|
| Ex   | Excellent                                       |
| Gd   | Good                                            |
| TA   | Typical - slight dampness allowed                |
| Fa   | Fair - dampness or some cracking or settling     |
| Po   | Poor - Severe cracking, settling, or wetness      |
| nan  | No Basement                                     |


- `bsmt_exposure` : Refers to walkout or garden level walls. (Ordinal)
| Code | Description                         |
|------|-------------------------------------|
| Gd   | Good Exposure                       |
| Av   | Average Exposure (split levels or foyers typically score average or above) |
| Mn   | Minimum Exposure                    |
| No   | No Exposure                         |
| nan  | No Basement                         |


- `bsmtfin_type_1` : Rating of basement finished area. (Ordinal)
| Code | Description                          |
|------|--------------------------------------|
| GLQ  | Good Living Quarters                 |
| ALQ  | Average Living Quarters              |
| BLQ  | Below Average Living Quarters        |
| Rec  | Average Rec Room                     |
| LwQ  | Low Quality                          |
| Unf  | Unfinished                           |
| nan  | No Basement                          |


- `bsmtfin_type_2` : Rating of basement finished area (if multiple types). (Ordinal)
| Code | Description                          |
|------|--------------------------------------|
| GLQ  | Good Living Quarters                 |
| ALQ  | Average Living Quarters              |
| BLQ  | Below Average Living Quarters        |
| Rec  | Average Rec Room                     |
| LwQ  | Low Quality                          |
| Unf  | Unfinished                           |
| nan  | No Basement                          |

- `heating` : Type of Heating. (Nominal)
| Code | Description                           |
|------|---------------------------------------|
| Floor | Floor Furnace                         |
| GasA  | Gas forced warm air furnace           |
| GasW  | Gas hot water or steam heat           |
| Grav  | Gravity furnace                       |
| OthW  | Hot water or steam heat other than gas|
| Wall  | Wall furnace                          |


- `heating_qc` : Heating quality and condition. (Ordinal)
| Code | Description    |
|------|----------------|
| Ex   | Excellent      |
| Gd   | Good           |
| TA   | Average/Typical|
| Fa   | Fair           |
| Po   | Poor           |


- `central_air` : Central air conditioning. (Nominal)
| Code | Description |
|------|-------------|
| N    | No          |
| Y    | Yes         |


- `electrical` : Electrical system. (Nominal)
| Code  | Description                                      |
|-------|--------------------------------------------------|
| SBrkr | Standard Circuit Breakers & Romex                |
| FuseA | Fuse Box over 60 AMP and all Romex wiring (Average) |
| FuseF | 60 AMP Fuse Box and mostly Romex wiring (Fair)  |
| FuseP | 60 AMP Fuse Box and mostly knob & tube wiring (Poor)  |
| Mix   | Mixed                                            |
| nan   | No Elecrical System                              |

- `kitchen_qual` : Kitchen Quality. (Ordinal)
| Code | Description  |
|------|--------------|
| Ex   | Excellent    |
| Gd   | Good         |
| TA   | Typical/Average |
| Fa   | Fair         |
| Po   | Poor         |


- `functional` : Home functionality (Assume typical unless deductions are warranted). (Ordinal)
| Code | Description             |
|------|-------------------------|
| Typ  | Typical Functionality   |
| Min1 | Minor Deductions 1      |
| Min2 | Minor Deductions 2      |
| Mod  | Moderate Deductions     |
| Maj1 | Major Deductions 1      |
| Maj2 | Major Deductions 2      |
| Sev  | Severely Damaged        |
| Sal  | Salvage only            |


- `fireplace_qu` : Fireplace Quality. (Ordinal)
| Code | Description                                    |
|------|------------------------------------------------|
| Ex   | Excellent - Exceptional Masonry Fireplace     |
| Gd   | Good - Masonry Fireplace in main level         |
| TA   | Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement |
| Fa   | Fair - Prefabricated Fireplace in basement     |
| Po   | Poor - Ben Franklin Stove                      |
| nan   | No Fireplace                                   |

- `garage_type` : Garage Location. (Nominal)
| Code    | Description                                               |
|---------|-----------------------------------------------------------|
| 2Types  | More than one type of garage                              |
| Attchd  | Attached to home                                          |
| Basment | Basement Garage                                           |
| BuiltIn | Built-In (Garage part of house - typically has room above garage) |
| CarPort | Car Port                                                  |
| Detchd  | Detached from home                                        |
| nan      | No Garage                                                 |


- `garage_finish` : Interior finishing of garage. (Ordinal)
| Code | Description |
|------|-------------|
| Fin  | Finished    |
| RFn  | Rough Finished |
| Unf  | Unfinished  |
| nan   | No Garage   |


- `garage_qual` : Garage quality. (Ordinal)
| Code | Description  |
|------|--------------|
| Ex   | Excellent    |
| Gd   | Good         |
| TA   | Typical/Average |
| Fa   | Fair         |
| Po   | Poor         |
| nan   | No Garage    |


- `garage_cond` : Garage Condition. (Ordinal)
| Code | Description      |
|------|------------------|
| Ex   | Excellent        |
| Gd   | Good             |
| TA   | Typical/Average  |
| Fa   | Fair             |
| Po   | Poor             |
| nan   | No Garage        |


- `paved_drive` : Paved Driveway. (Ordinal)
| Code | Description         |
|------|---------------------|
| Y    | Paved               |
| P    | Partial Pavement    |
| N    | Dirt/Gravel         |


- `pool_qc` : Pool Quality. (Ordinal)
| Code | Description      |
|------|------------------|
| Ex   | Excellent        |
| Gd   | Good             |
| TA   | Average/Typical  |
| Fa   | Fair             |
| nan   | No Pool          |


- `fence` : Fence Quality. (Ordinal)
| Code  | Description        |
|-------|--------------------|
| GdPrv | Good Privacy       |
| MnPrv | Minimum Privacy    |
| GdWo  | Good Wood          |
| MnWw  | Minimum Wood/Wire  |
| nan    | No Fence           |


- `misc_feature` : Miscellaneous feature not covered in other categories. (Nominal)
| Code | Description                     |
|------|---------------------------------|
| Elev | Elevator                        |
| Gar2 | 2nd Garage (if not described in garage section) |
| Othr | Other                           |
| Shed | Shed (over 100 SF)              |
| TenC | Tennis Court                    |
| nan   | None                            |


- `sale_type` : Type of Sale. (Nominal)
| Code | Description                              |
|------|------------------------------------------|
| WD   | Warranty Deed - Conventional             |
| CWD  | Warranty Deed - Cash                    |
| VWD  | Warranty Deed - VA Loan                 |
| New  | Home just constructed and sold          |
| COD  | Court Officer Deed/Estate               |
| Con  | Contract 15% Down payment regular terms |
| ConLw| Contract Low Down payment and low interest|
| ConLI| Contract Low Interest                   |
| ConLD| Contract Low Down                       |
| Oth  | Other                                  |


- `sale_condition` : Condition of sale. (Nominal)

| Code    | Description                                             |
|---------|---------------------------------------------------------|
| Normal  | Normal Sale                                             |
| Abnorml | Abnormal Sale - trade, foreclosure, short sale          |
| AdjLand | Adjoining Land Purchase                                 |
| Alloca  | Allocation - two linked properties with separate deeds, typically condo with a garage unit |
| Family  | Sale between family members                             |
| Partial | Home was not completed when last assessed (associated with New Homes) |



