# Netscreen_to_Forti
This python code is to convert the Netscreen cli configuration to Fortigata CLi for firewall addresses. This will be helpful in migration firewall address from a netscreen firewall to a fortigate firewall.
Y

Step 1: You need to convert the netscreen firewall addresses to the below format and save this in CSV format. In this project this csv file is named as TEST123.csv

Affari_10.88.10.88/29	10.88.10.88	255.255.255.248
Banca_10.73.7.128/25	10.73.7.128	255.255.255.128
BANCA_10.88.83.0/25	10.88.83.0	255.255.255.128
BNP_10.88.97.0/25	10.88.97.0	255.255.255.0
BNP_10.88.98.0/25	10.88.98.0	255.255.255.0

Step 2. You need to get the list of addresses that you need to migrate in the below format and save in CSV format. In this project this CSV filr is named as TEST1234.csv

Flow_10.228.4.0/29
h_10GTestSAP_10.228.20.128/25
h_10GTestSAP_10.228.84.128/25
h_ACEA_ELEC_10.78.113.88
h_Activ_Finance_10.179.0.15
h_Active_Financial_10.22.25.128/25
h_Aletti_10.78.134.88/29

Step3: Run the code.
This will check the required 



