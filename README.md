# first_order_logic_demo
This project utilizes a First-Order Logic Knowledge Base (FolKB) and the forward chaining algorithm to predict the resignation of prime ministers based on a set of logical rules and facts. The rules are derived from a given paragraph and general knowledge about the implications of certain events on a prime minister's position.

“Boris Johnson is the prime minister of UK. Sanna Marin is the prime minister of Finland. Videos of
parties at the Downing Street attended by Boris Johnson were publicly leaked. Videos of private
parties attended by Sanna Miran were publicly leaked. The Downing Street parties violated Covid-19
lockdown laws. Social gatherings violating Covid-19 lockdown laws are illegal. The prime minister of
a country who attends illegal parties is disapproved by the citizens of that country. The prime
minister of a country who is disapproved by its citizens loses their trust. The prime minister of a
country resigns from the prime minister post after losing its citizens' trust.”

Part I: Creating the FolKB
The FolKB is created based on the information provided in the given paragraph. General knowledge is also included to complete the knowledgebase. 

Part II: Predicting Resignations
The file contains the implementation of the forward chaining algorithm (fol_fc_ask). You can execute the inference process.

Results
The program will display the intermediate steps in the inference process, including the determination of who resigns from the prime minister post based on the provided facts and rules.
