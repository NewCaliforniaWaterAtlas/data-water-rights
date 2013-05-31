# New California Water Atlas: Data - Water Rights
--------------------------------------------------------------------------------

(DRAFT)

##About this repository

Improved water rights data for California.
- Using eWWRIMS data from State Water Resource Control Board

How we are improving the data:
- Seeking real time data
- Documenting the various fields in partnership with the State Water Resource Control Board
- Attempting to get dataset into data.ca.gov

@TODO Add data set, finish documenting this

--------------------------------------------------------------------------------
New California Water Atlas
Making Water Understandable in California
http://ca.statewater.org  @CAStateWater

California Water Rights interactive
http://ca.statewater.org/water-rights
Launched April 2013. Update planned for August 2013.

Water Rights Workgroup on New California Water Atlas website:
http://ca.statewater.org/water-rights  (currently: http://live-ca-statewater.gotpantheon.com/water-rights)

This repository location:
https://github.com/NewCaliforniaWaterAtlas/data-water-rights.git

Contributors
- Chach Sikes @chachasikes (Data research, documentation)
- Ted Gratham UC Davis Department of Watershed Sciences (possibly)

Work done as part of California Water Rights project, incubated by the Resource Renewal Institute http://rri.org with financial support from Patagonia. http://patagonia.com.

If you are interested in helping to make water rights data better in California, please contact the New California Water Atlas at info@statewater.org.


## Install Mongo Database
--------------------------------------------------------------------------------
@TODO Document

## Export Mongo Database as CSV file
--------------------------------------------------------------------------------
@TODO Document

## How to obtain the original files
--------------------------------------------------------------------------------

### eWRIMS data
@TODO Document
Steps:


Features

@TODO Document ID's

## References

---------------------------------------------------------------------------------

Data
Current database is MongoDB:

@TODO Document all of these fields and where they came from.
@TODO Add a few different examples: individual, state water project, municipal project, farm
```json
{
        "id" : "C003105_01",
        "kind" : "right",
        "type" : "Feature",
        "coordinates" : [
                -119.70260375,
                37.24426798
        ],
        "geometry" : {
                "type" : "Point",
                "coordinates" : [
                        -119.70260375,
                        37.24426798
                ]
        },
        "properties" : {
                "id" : "C003105_01",
                "kind" : "right",
                "source" : "http://gispublic.waterboards.ca.gov/",
                "name" : "JOE  ALBERTA",
                "pod_id" : "01",
                "water_right_id" : "13601",
                "pod_number" : "01",
                "application_id" : "C003105",
                "direct_div_amount" : "0.0",
                "diversion_storage_amount" : "2.5",
                "diversion_acre_feet" : "0.0",
                "place_id" : 663256,
                "pod_status" : "Active",
                "face_value_amount" : "0.0",
                "diversion_type" : "Direct Diversion",
                "diversion_code_type" : "Diversion point",
                "water_right_type" : "Stockpond",
                "water_right_status" : "Certified",
                "storage_type" : "",
                "pod_unit" : "Gallons per Day",
                "first_name" : "JOE",
                "holder_name" : "ALBERTA",
                "organization_type" : "Individual",
                "application_pod" : "C003105_01",
                "township_number" : "8",
                "range_direction" : "E",
                "township_direction" : "S",
                "range_number" : "21",
                "section_number" : "8",
                "section_classifier" : "",
                "quarter" : "SW",
                "quarter_quarter" : "SE",
                "meridian" : "Mount Diablo",
                "northing" : "1912401",
                "easting" : "6793775",
                "sp_zone" : "3",
                "latitude" : 37.24426798,
                "longitude" : -119.70260375,
                "trib_desc" : "",
                "location_method" : "DD_NE",
                "source_name" : "UNST",
                "moveable" : "N",
                "has_opod" : "N",
                "watershed" : "AHWAHNEE",
                "county" : "Madera",
                "well_number" : "   ",
                "quad_map_name" : "O'NEALS",
                "quad_map_num" : "JJ023 ",
                "quad_map_min_ser" : "7.5",
                "parcel_number" : "",
                "special_area" : null,
                "last_update_user_id" : 9,
                "date_last_updated" : 1191046438000,
                "status" : "Certified",
                "ewrims_db_id" : "13976",
                "reports" : {
                        "2009" : {
                                "usage" : [
                                        "Other"
                                ],
                                "usage_quantity" : [
                                        " 6054 Ac. Waterfowl Habitat, and Rice Straw Decomp. "
                                ],
                                "diversion_unit" : "Acre-Feet",
                                "total_diverted" : 6466,
                                "total_used" : 6466,
                                "diversion_total" : "6466",
                                "used_total" : "6466",
                                "amount_diverted" : [
                                        {
                                                "January" : "1028"
                                        },
                                        {
                                                "February" : "0"
                                        },
                                        {
                                                "March" : "0"
                                        },
                                        {
                                                "April" : "0"
                                        },
                                        {
                                                "May" : "0"
                                        },
                                        {
                                                "June" : "0"
                                        },
                                        {
                                                "July" : "0"
                                        },
                                        {
                                                "August" : "0"
                                        },
                                        {
                                                "September" : "0"
                                        },
                                        {
                                                "October" : "0"
                                        },
                                        {
                                                "November" : "3703"
                                        },
                                        {
                                                "December" : "1735"
                                        },
                                        {
                                                "Total" : "6466"
                                        }
                                ],
                                "amount_used" : [
                                        {
                                                "January" : "1028"
                                        },
                                        {
                                                "February" : "0"
                                        },
                                        {
                                                "March" : "0"
                                        },
                                        {
                                                "April" : "0"
                                        },
                                        {
                                                "May" : "0"
                                        },
                                        {
                                                "June" : "0"
                                        },
                                        {
                                                "July" : "0"
                                        },
                                        {
                                                "August" : "0"
                                        },
                                        {
                                                "September" : "0"
                                        },
                                        {
                                                "October" : "0"
                                        },
                                        {
                                                "November" : "3703"
                                        },
                                        {
                                                "December" : "1735"
                                        },
                                        {
                                                "Total" : "6466"
                                        }
                                ],
                                "year" : "2009",
                                "ewrims_db_id" : "13976",
                                "ewrims_form_id" : "37516"
                        }
                },
                "source_alt" : "http://ciwqs.waterboards.ca.gov/",
                "date_received" : "",
                "date_accepted" : "01/06/1978",
                "date_notice" : "",
                "protest" : "",
                "number_protests" : "0",
                "agent_name" : "",
                "agent_entity_type" : "",
                "primary_owner" : "JOE  ALBERTA",
                "primary_owner_entity_type" : "Individual",
                "face_value_units" : "Acre-feet per Year",
                "max_dd_appl" : "0.0",
                "max_dd_units" : "Gallons per Day",
                "max_dd_ann" : "0.0",
                "max_storage" : "2.5",
                "max_use_appl" : "0.0",
                "year_first_use" : "1968.0",
                "effective_from_date" : "09/15/1994",
                "effective_to_date" : "",
                "entity_type" : "Individual",
                "name_type" : "Primary Owner",
                "mailing_street_number" : null,
                "mailing_street_name" : null,
                "mailing_address_line2" : null,
                "mailing_city" : null,
                "mailing_state" : null,
                "mailing_country" : null,
                "mailing_zipcode" : null,
                "billing_street_number" : null,
                "billing_street_name" : null,
                "billing_city" : null,
                "billing_state" : null,
                "billing_country" : null,
                "billing_zipcode" : null,
                "phone" : null,
                "use_code" : "Stockwatering",
                "use_status_new" : "Migrated from old WRIMS data",
                "use_population" : "0",
                "use_net_acreage" : "0.0",
                "use_gross_acreage" : "0.0",
                "use_dd_annual" : "0.0",
                "use_dd_rate" : "",
                "use_dd_rate_units" : "",
                "use_storage_amount" : "2.5",
                "use_seasons" : "",
                "direct_div_season_begin_date" : null,
                "direct_div_season_end_date" : null,
                "direct_div_season_div_rate" : "",
                "direct_div_season_div_rate_units" : "",
                "direct_div_season_annual_amount" : "",
                "storage_season_begin_date" : null,
                "storage_season_end_date" : null,
                "storage_season_amount" : "2.5",
                "pod_max_dd" : "0.0",
                "source_max_dd_unit" : "",
                "pod_max_storage" : "0.0",
                "source_max_storage_unit" : "Gallons per Day",
                "pod_gis_maintained_data" : "",
                "appl_id" : "C003105",
                "podid" : "3912",
                "permit_id" : "",
                "water_right_description" : "",
                "issue_date" : "1979-03-26",
                "construction_completed_by" : "",
                "planned_project_completion_date" : "",
                "permit_terms" : "",
                "term_id" : "0000021",
                "version_number" : "2.0"
        },
        "_id" : ObjectId("50f334c57ed9c041de0000dc")
}
```





