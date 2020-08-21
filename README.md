# covid_industries
Essential vs. non-essential covid industries

This repository contains the list of industries deemed "essential" during the spread of COVID-19. 

The data is hand collected by MIT researchers, Olivia Kim, Antoinette Schoar, and Jonathan Parker, based on the "Essential Critical Infrastructure Workforce" advisory list of the Department of Homeland Security (HLS).
As noted in the HLS memorandum (https://www.cisa.gov/sites/default/files/publications/Version_3.1_CISA_Guidance_on_Essential_Critical_Infrastructure_Workers_0.pdf), this list is intended to help State, local, tribal and territorial officials to make informed decisions, and should not be considered a federal directive. 
Therefore, individual jurisditcitons may differ in their own requirements of essential vs. non-essential distinctions. 

We provide this data free of restrictions, but ask that you attribute the data to our research team. The data is provided under a Creative Commons Public License.

The original data sources are:
1. The Cybersecurity and Infrastructure Security Agency (CISA) of the U.S. Dept. of HLS: 
https://www.cisa.gov/sites/default/files/publications/Version_3.1_CISA_Guidance_on_Essential_Critical_Infrastructure_Workers_0.pdf
2. The list compiled by the Governor's office of Pennsylvania:
https://www.governor.pa.gov/wp-content/uploads/2020/03/20200319-Life-Sustaining-Business.pdf

The excel file contains the following information:
- NAICS code: 6-digit naics code
- NAICS industry title: 6-digit industry label
- HLS industry name: HLS label of essential industry
- source_hls: an indicator that equals 1 if the information was collected from the HLS
- source_penn: an indicator that equals 1 if the information was collected from the Penn list
- d_uncertain: an indicator that equals 1 if we are not 100% certain whether an industry is considered essential vs. non-essential. 
