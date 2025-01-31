# Acquisition of data from API
## The background
Getting real-time weather data from the KNMI website
## Methodology and data source used
Open Data API 
![API1](https://github.com/user-attachments/assets/06a6d500-9df0-4367-8c6b-c95706b1cc17)
## Details about the implementation
1. get the key for authentication so that the data can be accessed
![authentication key](https://github.com/user-attachments/assets/fe0b745e-ec07-4f10-8c13-546ddd39a268)
2. put the key in the KNMI data platform to authorize the availability of data
3. input the name and the version of the dataset in the form (the maximum number of files to return could also be adjusted)
![image](https://github.com/user-attachments/assets/95addef6-f1ff-4350-a1ac-289e97c65557)
4. click “execute” in the first section to obtain the paginated list of files for the dataset
![image](https://github.com/user-attachments/assets/0148d379-0c3e-4e3c-821f-688d866d1adc)
5. input the filename in the second section to get the download link
![image](https://github.com/user-attachments/assets/a24f1bd1-dfbb-46bb-a0d0-9661b0fb054f)
![download link](https://github.com/user-attachments/assets/e4a819f9-d0a9-4bd0-a7c7-f3fa55632e8b)
6. code: see [Acquisition of data from API.ipynb](https://github.com/be325/GRS35306/blob/main/Acquisition%20of%20data%20from%20API.ipynb) (provided by Nikshep, Bangalore Suresh)
## Results
the file could be downloaded but in tar. format
## Conclusions both on the results as well as on the accomplishment of the goal
The file is in tar format and requires specific software to present. The goal of obtaining data through API is accomplished.
