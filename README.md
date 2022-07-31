# WaferDCGAN
In this notebook, we ill build a simple DCGAN to generate synthetic images of WM-811k data. WM-811K is an open source dataset that include semiconductor WBM collected from 46,393 lots in real-world semiconductor industries. The same logic for WBM applies here such that defective dies have logic `1' and normal dies are represented by logic `0'. The properties included in the WM-811K dataset are waferMap, dieSize, lotName, waferIndex, trainTestLabel, and failureType. In total the data consists of 811,475 WBMs, 21.3% of the WBMs in the dataset have labels. Among labeled WBMs, 3.1% have failure patterns while 18.2\% do not have patterns. The failure patters are eight in total namely Centre, Donut, Edge-Loc, Edge-Ring, Loc, Near-Full, Random, and Scratch. 



Figure \ref{fig:subpie} summarises the distribution of data for WM-811k dataset. In this code, we considered the Donut class in order to generate sythetic images form

![alt text](https://github.com/AbuEbayyeh/waferDCGAN/blob/main/images/wm811k.PNG)

