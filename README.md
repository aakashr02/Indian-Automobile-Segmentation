This is a Data Analytics and Machine Learning project to analyze and segment the car models and its variants in the Indian market using unsupervised algorithms like K-Medoids and K-Prototypes clustering. The results would help automobile brands identify competing car models from other manufacturers.

## Architecture
![image](https://github.com/aakashr02/Indian-Automobile-Segmentation/assets/87864552/60799714-7b13-46b4-97ac-deff51d270e3)

## Results
###### 1. K-Medoids
The following were the cluster centers for the 7 strategic groups obtained using K-Medoids clustering
![image](https://github.com/aakashr02/Indian-Automobile-Segmentation/assets/87864552/28e60b32-b7ac-4bb0-91c7-49bacb857e3b)

###### 2. K-Prototypes
The following were the cluster centers for the 2 strategic groups obtained using K-Prototypes clustering
![image](https://github.com/aakashr02/Indian-Automobile-Segmentation/assets/87864552/39111dcc-b290-4ac5-9a2f-8499d5f247a9)

## Performance Evaluation
![image](https://github.com/aakashr02/Indian-Automobile-Segmentation/assets/87864552/b8c315ed-3bac-483e-ac41-14622365c22c)

Based on the Calinski Harabasz Index and the Dunn Index, K-Prototype algorithm 
seems to perform well than the K-Medoids algorithm with minimum between cluster 
similarities. Higher values of Calinski Harabasz Index and the Dunn Index support 
this.

## Results
A few results obtained are as below -
1) Brands Positions
Maruti Suzuki, Tata, Mahindra, Hyundai have clearly positioned themselves only in 
the economic and basic segment, largely targeting middle class consumers. It can be 
clearly seen from the clustering results that the above Makers occur only in the Basic 
Sedans, Hatchbacks and thus they are strong competitors of each other when it 
comes to the economic market. Likewise, Mercedes, BMW, Audi, Porsche and 
Jaguar compete with each other in the Luxury segment. They are prime 
manufacturers of sporty and luxury sedans.
2) Honda City vs Honda Amaze
Honda City is a higher priced and premium sedan than Honda Amaze, but that does 
not seem true from the clustering results. Both car models are grouped into the same 
segment, which may not be the desired target market perceived by Honda. This 
suggests that Honda City being a premium car model than a more basic Honda 
Amaze, may often be perceived alike by most consumers.
3) Unpopularity of Isuzu Mu-X
Isuzu, a Japanese car manufacturer, did not make much in the Indian automobile 
market. From 2013 until March 2022, only 2598 units of the car were sold. This 
could possibly be because of tough competitors in its cluster like Toyota Innova 
Crysta and Hyundai Creta which are highly sought after by buyers. Isuzu ' s failure 
may be because of their choice of target market - the SUV segment ruled by well 
established brands like Toyota and Hyundai.
27 Indian Automobile Strategic Grouping
4) Volkswagen Ameo is a perfect successor to Volkswagen Vento
Volkswagen wanted to introduce Ameo as a replacement to Volkswagen Vento, 
which seems successful from the clustering results. Both the car models occur in the 
low end sedan segment and hence indicates how Volkswagen continues its hold in 
the low end sedan segment.
5) Toyota Fortuner vs Ford Endeavour
The clustering result suggests a tough competition between Toyota Fortuner and 
Ford Endeavour. Both occurring in the Luxury Crossovers & SUVs segment, Ford' 
s Endeavour competes with Toyota ' s Fortuner in every aspect including price, 
displacement and mileage. 
6) Skoda Superb's Competitors
Skoda Superb competes with Volkswagen Passat and even the basic models from 
Mercedes and Audi in the luxury sedan segment. Because of an equal competition 
in the market between the cars in this segment, none outstands the other. This 
segment is equally held by makers like Mercedes, Volkswagen, Skoda and Audi.
7) Hyundai Creta vs Hyundai Tucson
Hyundai is a competitor to itself when it comes to Creta vs Tucson. The newly 
launched Tucson is not as sought after as Creta. Annual sales of Creta was 1,40,895 
in 2022 while Tuscon was only a few thousands. Both occur in the Crossover & 
SUV segment and hence the same target market. This means that trying to increase 
the sales of one model will bring down the sales of the other.
8) Maruti Suzuki's Monopoly
Clearly seen from the Clustering results, Maruti Suzuki dominates the Hatchback 
segment with a total of 15 car models and contributes a 33% market share in this 
strategic group. Maruti Suzuki thus holds a major share in the Indian automobile 
market, primarily dominating the hatchback segment.

For an in depth understanding of the project look at the Documentation Folder of this repository.


