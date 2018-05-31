# deep-learning-gpu-box-build-instructions
Instructions and parts for building a deep learning GPU box    

## Parts   

| Part | Brand / Link | Purpose | Quantity | Optional? |
|---|---|---|---|---|
| SSD | [Samsung 850 evo (250 GB)](https://www.amazon.com/gp/product/B00OAJ412U/ref=oh_aui_detailpage_o08_s01?ie=UTF8&psc=1)   | OS + working dir   | 1   | N|
| SSD | [Samsung 850 evo (1 TB)](https://www.amazon.com/gp/product/B00OBRFFAS/ref=oh_aui_detailpage_o08_s01?ie=UTF8&th=1)   | fast data loading. Keep datasets not in use on the SSHD   | 1+   | N |
| SSHD | [Seagate FireCuda (2TB)](https://www.amazon.com/gp/product/B01IEKG2HM/ref=oh_aui_detailpage_o05_s00?ie=UTF8&psc=1)   | data storage, long term model storage | 1+   | Y |
| Processor | [Intel i7 (6+ cores)](https://www.amazon.com/gp/product/B01FJLAITC/ref=oh_aui_detailpage_o08_s00?ie=UTF8&psc=1)   | At least 1 core per GPU | 1 | N |
| Power source | [Corsair 1500 W](https://www.amazon.com/gp/product/B00MFJ4OBA/ref=oh_aui_detailpage_o07_s03?ie=UTF8&psc=1)   | Enough for 4 gpus | 1 | N |
| Motherboard | [Asus X99-E WS](https://www.amazon.com/gp/product/B00XUDLXJG/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1)   | Big enough for 4 GPUs | 1 | N |  
| RAM | [Crucial (16GB+ each)](https://www.amazon.com/gp/product/B019FRBCQE/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1)   | You need at least as much RAM as GPU RAM | 4 | N |  
| Tower | [Phanteks Enthoo Pro](https://www.amazon.com/dp/B00K6S1B3Q/ref=dp_prsubs_2) | Big enough for 4 GPUs | 1 | N |   
| GPUs | [NVIDIA 1080Ti](https://www.amazon.com/gp/product/B06Y13N2B6/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1) | Go with 12 GB RAM. Best price/teraflops+RAM out there. (Optional jet fans vs open fan. I use both) | 4 | N |   
| CPU Water Cooler | [Corsair CW-9060027-WW Hydro Series H115i](https://www.amazon.com/gp/product/B019955RNQ/ref=oh_aui_detailpage_o07_s02?ie=UTF8&psc=1) | Try to keep the overall temp in the box down or GPUs will throttle. (Optional but HIGHLY recommended) | 1 | Y |   
| Small Fans | [Corsair ML120 Pro LED](https://www.amazon.com/gp/product/B01G5I6MUW/ref=oh_aui_detailpage_o06_s00?ie=UTF8&psc=1) | Replace front and bottom pannel fans. These are more quiet than the stock fans | 3 | Y |   
| Large Fans | [Corsair ML140 Pro LED](https://www.amazon.com/gp/product/B01G5I6Q94/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1) | Assuming you get rid of the tower stock fans. (Highly recommended) | 4 | Y |   
| FAN connectors | [4Pin PWM to 3Pin](https://www.amazon.com/gp/product/B01H0OZC9W/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1) | You'll run out of fan connectors with new fans | 1 | Y |   


    

