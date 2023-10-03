# NPS2001A_Group-assignment_Automated Recycling Bin
The purpose of this project is to create a prototype that addresses our identified issue of poor recycling rates among Singaporeans.

## Needed data
Our recycling bin employs at least 3 image classifiers and sorting algorithms when sorting the object that enters the bin. We tapped into either existing algorithms or databases that we'll feed into the machine learning model to sort the object. 

### First level: Sorting Recyclable from Non-Recyclable
For the bin to classify recyclables from non-recyclables, we'll utilise existing algorithms and databases such as [RecycleSorter](https://github.com/iancheung0202/RecycleSorter) and a dynamic database - [Google Drive](https://drive.google.com/drive/folders/1ajtfqsc5DEYgkiVz43b6S38CAW67r2VX?usp=sharing) created by the team to compile images of Recyclables and Non-recyclables. 
Other databases we'll reference: [Singapore's guidelines on recyclables](https://www.nea.gov.sg/docs/default-source/our-services/waste-management/list-of-items-that-are-recyclable-and-not.pdf)

### Second level: Sorting Clean Recyclables from Contaminated Recyclables
To classify and sort clean recyclables from contaminated recyclables, the team created a dynamic database - [Google drive](https://drive.google.com/drive/folders/1ajtfqsc5DEYgkiVz43b6S38CAW67r2VX?usp=sharing) - with photos of clean and contaminated recyclables to feed into the [machine learning model](https://teachablemachine.withgoogle.com/models/yxGdKb3qR/)

### Third level: Sorting Clean Glass from Clean Plastic 
To classify and sort clean glass from clean plastic, the team will utilise [existing database and algorithm found on GitHub](https://github.com/jenkspt/recycle) 

### Implicit Feedback: User engagement and bin's accuracy rate


