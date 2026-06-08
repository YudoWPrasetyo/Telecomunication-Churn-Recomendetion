# Telecomunication ChurnRecomendetion

## Indonesia

Konteks:
Perusahaan telekomunikasi adalah perusahaan yang menyediakan infrastruktur bagi masyarakat untuk berkomunikasi melalui transmisi elektronik. Orang dapat berlangganan berbagai paket yang ditawarkan oleh setiap penyedia telekomunikasi seperti koneksi internet, pesan, telepon, dll. Dengan perkembangan teknologi di setiap sektor, konektivitas semakin dibutuhkan dan perusahaan telekomunikasi memainkan peran besar di era informasi ini. 

Tujuan:
Sebuah perusahaan Telekomunikasi telah memiliki data yang berisi detail pelanggannya dan riwayat penggunaan mereka. Dengan data yang tersedia, perusahaan ingin memperoleh nilai darinya dengan mengolahnya untuk mendapatkan wawasan dan model prediktif untuk penggunaannya. Model prediktif akan dibangun untuk memprediksi probabilitas churning pelanggan.

## English

Contex:
Telecommunication company is a company that provides infrastructure for people to communicate through electronic transmission. People could subscribe to different plan offered by each telecommunication provider such as internet connection, messaging, telephone, etc. With the development of technology in each sector, connectivity is more needed than ever and telecomunication company played a big role in this information era.  

Goals:
A Telecomunication company has possessed data which contains it's customer's details and their usage history. With the data available, the company wanted to obtain value from it by processing it to get insights and predictive models for its uses. The predictive model will be built to predict customer probability of churning.



## STAR

Situation : The company faced significant challenges in retaining users within a highly competitive telecommunications market. While a vast dataset containing customer profiles and service usage history was available, it had not been optimally leveraged to identify behavioral patterns of customers at risk of quitting the service (churning).
Task : Conduct a deep-dive analysis into customer behavior and build a predictive machine learning model to estimate churn probability, enabling the management team to implement targeted preventive retention strategies.
Action : Performed Exploratory Data Analysis (EDA) using Python/SQL to map out customer loyalty metrics against their length of service (tenure), Processed demographic variables and product features (internet, telephone, and messaging services) to train robust classification models, such as Random Forest and XGBoost, Pinpointed critical business pain points by visualizing the distribution data of customer churn.
Result : Successfully identified that 49.38% of all churn cases were heavily concentrated within the first 10 months of subscription, with a critical surge in the initial phase: 36.38% at 0–5 months tenure and 13.00% at 5–10 months tenure. Discovered a clear pattern showing that churn risk decreases drastically as customer loyalty builds—dropping to 9.42% in months 10–15 and hitting a record low of 1.66% among long-term customers (70–75 months tenure) Delivered these predictive insights to the product and marketing teams to design an intensive onboarding program tailored specifically for the first 5 months, significantly boosting new customer retention rates.
