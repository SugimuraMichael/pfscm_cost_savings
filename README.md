# pfscm_cost_savings
cost-savings

Main file is the fcpk_savings_v2 file. it injests a PAD COR dataset and outputs cost savings based on fcpk
the main benefit. the standard is to compare one year against another, additional functionality will be needed in 2018

output is a long dataset that keeps track of 'savings" per lane 

savings calculated as (2017 Shipped Weights X (2016 Freight Cost/2016 Shipped Weights)) - (Actual Cost to Ship 2017 Weights)

positive values are good, negative values are bad

NOTE: this analysis is based on 10 countries which were the most frequently used in 2016, idea at the time of design was that these would serve as a very stable base to compare against. This will also have to be updated overtime

country_list = ['Mozambique', 'Tanzania', 'Uganda', 'Nigeria', 'Malawi', 'Ghana',
                    'Zimbabwe', 'Zambia', 'Guinea', "C\xf4te d'Ivoire"]
                    
                    
