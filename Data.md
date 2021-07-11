# Data

You can find the list of districts in Surabaya [here](https://id.wikipedia.org/wiki/Daftar_kecamatan_dan_kelurahan_di_Kota_Surabaya).

There is no public dataset to retrieve the coordinates of each distric in Surabaya, so I collect them manually. After that I create the clean dataset that contain latitude and longitude features. You can googling the exact coordinate but it returns with WGS84 datum format. You can get the latitude and logitude by convert it in [here](https://www.earthpoint.us/Convert.aspx). 

We can use Forsquare API to get the most common food venues of given district of Surabaya. For each district, we have chosen the radius to be 500 meter.