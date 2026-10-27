# Hướng dẫn kéo dài tuổi thọ dành cho lập trình viên

[![Tài liệu CN](https://img.shields.io/badge/文档-中文版-blue.svg)](README.md)
[![Tài liệu EN](https://img.shields.io/badge/document-English-blue.svg)](README_en.md)
[![Tài liệu VI](https://img.shields.io/badge/document-Tiếng_Việt-blue.svg)](README_vi.md)
[![MetaGPT](https://img.shields.io/badge/ít_việc_hơn-MetaGPT-blue)](https://github.com/geekan/MetaGPT)

- [1. Thuật ngữ](#1-thuật-ngữ)
- [2. Mục tiêu](#2-mục-tiêu)
- [3. Kết quả then chốt](#3-kết-quả-then-chốt)
- [4. Phân tích](#4-phân-tích)
- [5. Hành động](#5-hành-động)
- [6. Bằng chứng](#6-bằng-chứng)
  - [6.1. Đầu vào](#61-đầu-vào)
    - [6.1.1. Thực phẩm rắn](#611-thực-phẩm-rắn)
    - [6.1.2. Chất lỏng](#612-chất-lỏng)
    - [6.1.3. Chất khí](#613-chất-khí)
    - [6.1.4. Ánh sáng](#614-ánh-sáng)
    - [6.1.5. Thuốc](#615-thuốc)
  - [6.2. Đầu ra](#62-đầu-ra)
    - [6.2.1. Các môn thể thao dùng vợt](#621-các-môn-thể-thao-dùng-vợt)
    - [6.2.2. Vận động cường độ cao](#622-vận-động-cường-độ-cao)
    - [6.2.3. Đi bộ](#623-đi-bộ)
    - [6.2.4. Đánh răng](#624-đánh-răng)
    - [6.2.5. Tắm ngâm](#625-tắm-ngâm)
    - [6.2.6. Làm việc nhà (nam giới cao tuổi)](#626-làm-việc-nhà-nam-giới-cao-tuổi)
    - [6.2.7. Giấc ngủ](#627-giấc-ngủ)
    - [6.2.8. Ngồi lâu](#628-ngồi-lâu)
  - [6.3. Bối cảnh](#63-bối-cảnh)
    - [6.3.1. Cảm xúc](#631-cảm-xúc)
    - [6.3.2. Giàu nghèo](#632-giàu-nghèo)
    - [6.3.3. Cân nặng](#633-cân-nặng)
    - [6.3.4. COVID-19](#634-covid-19)

---

### 1. Thuật ngữ

* ACM: All-Cause Mortality / Tỷ lệ tử vong do mọi nguyên nhân

### 2. Mục tiêu

* Sống lâu hơn một cách vững chắc
* Dành ít thời gian hơn cho công việc: xem [MetaGPT](https://github.com/geekan/MetaGPT)

### 3. Kết quả then chốt

* Giảm 66.67% tỷ lệ tử vong do mọi nguyên nhân
* Tăng \~20 năm tuổi thọ kỳ vọng
* ~~Duy trì dopamine ở mức trung tâm~~

### 4. Phân tích

* Tài liệu tham khảo chính: có tương đối nhiều tài liệu học thuật về ACM, có thể dùng làm nguồn tham khảo chính
* Quan hệ giữa tăng tuổi thọ và ACM là phi tuyến: rõ ràng, quan hệ giữa tăng tuổi thọ và ACM là một hàm phi tuyến; ở đây giả định `ΔLifeSpan=(1/(1+ΔACM)-1)*10` (ΔACM là mức thay đổi của ACM; hoan nghênh đề xuất cải tiến công thức)
* Không thể đơn giản cộng dồn các biến: rõ ràng, các biến không thỏa mãn giả định độc lập và cùng phân phối; ảnh hưởng thực tế giữa các biến cũng chưa rõ
* Có những quan điểm mâu thuẫn: mọi bằng chứng đều có tài liệu/nghiên cứu tương ứng, nhưng cần lưu ý: một số tài liệu có quan điểm mâu thuẫn đáng kể (chẳng hạn mâu thuẫn về tỷ lệ carbohydrate nạp vào); một số tài liệu gây tranh cãi lớn (chẳng hạn cho rằng đi ngủ trước 22 giờ làm tăng 43% tỷ lệ tử vong do mọi nguyên nhân)
* Nghiên cứu chỉ thể hiện mối tương quan: mọi tài liệu chủ yếu cho thấy tương quan chứ không phải quan hệ nhân quả; khi đọc, cần cân nhắc liệu tài liệu đã chứng minh đầy đủ quan hệ nhân quả hay chưa — chẳng hạn, một tài liệu cho thấy người đi trung bình >=7000 bước mỗi ngày có tỷ lệ tử vong do mọi nguyên nhân thấp hơn đáng kể. Nhưng nhóm đi ít bước có thể bao gồm nhiều người mắc bệnh lâu năm hơn; nếu không loại trừ hợp lý phần dữ liệu này thì kết quả khảo sát của tài liệu sẽ bị sai lệch

### 5. Hành động

* Đầu vào
  * Thực phẩm rắn: ăn thịt trắng (-11%\~-3% ACM), chủ yếu ăn rau quả (-26%\~-17% ACM), ăn cay nhiều hơn (-23% ACM), ăn nhiều hạt hơn (-27%\~-4% ACM), ăn lượng carbohydrate vừa phải, ăn nhiều protein thực vật hơn (-10% ACM), ăn ít thực phẩm siêu chế biến (-62%\~-18%)
  * Chất lỏng: uống cà phê (-22%\~-12% ACM), uống sữa (-17%\~-10% ACM), uống trà (-15%\~-8% ACM), hạn chế hoặc không uống đồ uống có vị ngọt (nếu không, mỗi ngày một cốc +7% ACM, +dopamine), bỏ rượu (nếu không +\~50% ACM, không có giới hạn trên)
  * Chất khí: không hút thuốc (nếu không +~50% ACM, -12\~-11 năm tuổi thọ)
  * Ánh sáng: phơi nắng (-~40% ACM)
  * Thuốc: metformin (người mắc đái tháo đường có thể sống thêm +3 năm so với người bình thường), vitamin tổng hợp (-8% nguy cơ ung thư), spermidine (-60%\~-30% ACM), glucosamine (-39% ACM)
* Đầu ra
  * Vận động: chơi môn thể thao dùng vợt 3 lần mỗi tuần, mỗi lần 45 phút (-47% ACM)
  * Hằng ngày: đánh răng (-25% ACM)
  * Giấc ngủ: ngủ 7 giờ mỗi ngày có tỷ lệ tử vong do mọi nguyên nhân thấp nhất; và tốt nhất là đi ngủ trong khoảng 22-24 giờ, *ngủ sớm +43% ACM, ngủ muộn +15% ACM (còn tranh cãi)*
* Bối cảnh
  * Cân nặng: giảm cân (-54% ACM)

### 6. Bằng chứng

#### 6.1. Đầu vào

##### 6.1.1. Thực phẩm rắn

* Thịt trắng
  * [Tạp chí thuộc JAMA: ăn thịt đỏ và thịt chế biến làm tăng nguy cơ mắc bệnh tim và tử vong! Cá và thịt gia cầm thì không](https://zhuanlan.zhihu.com/p/268401670)
    * Nguồn: [Associations of Processed Meat, Unprocessed Red Meat, Poultry, or Fish Intake With Incident Cardiovascular Disease and All-Cause Mortality](https://jamanetwork.com/journals/jamainternalmedicine/articlepdf/2759737/jamainternal_zhong_2020_oi_190112.pdf)
    * Tăng lượng thịt đỏ tiêu thụ có liên quan đến nguy cơ tử vong. Những người được khảo sát tăng lượng thịt đỏ tiêu thụ trung bình ít nhất nửa khẩu phần mỗi ngày trong tám năm (nửa khẩu phần thịt đỏ tương đương 14g thịt đỏ chế biến hoặc 40g thịt đỏ chưa chế biến) có nguy cơ tử vong do mọi nguyên nhân tăng 10％ trong tám năm tiếp theo (HR, 1.10; 95%CI, 1.04-1.17); ăn hai khẩu phần thịt đỏ hoặc thịt chế biến mỗi tuần (nhưng không bao gồm gia cầm hoặc cá) làm tăng 3% nguy cơ tử vong do mọi nguyên nhân
    * ![Thịt đỏ](https://user-images.githubusercontent.com/2707039/163703960-6f321de5-4daa-4ea5-95b9-af9c96f1c1bc.jpg)
  * [Khác biệt lớn nhất giữa thịt đỏ và thịt trắng là gì? Vì sao lại phân loại như vậy?](https://www.zhihu.com/question/67223570/answer/809785380)
* Rau quả
  * [540 nghìn người tử vong mỗi năm vì ăn quá ít trái cây!? Đây đã trở thành một trong mười yếu tố gây tử vong hàng đầu!](https://www.sohu.com/a/322360740_164924)
    * Nguồn: [Estimated Global, Regional, and National Cardiovascular Disease Burdens Related to Fruit and Vegetable Consumption: An Analysis from the Global Dietary Database (FS01-01-19) ](https://academic.oup.com/cdn/article-abstract/3/Supplement_1/nzz028.FS01-01-19/5516583)
    * Ăn 200 gam trái cây tươi mỗi ngày có thể làm giảm 17% tỷ lệ tử vong, giảm 13% nguy cơ biến chứng mạch máu lớn của đái tháo đường (như đột quỵ, bệnh tim thiếu máu cục bộ, v.v.) và giảm 28% nguy cơ biến chứng mạch máu nhỏ của đái tháo đường (như bệnh thận đái tháo đường, bệnh mắt đái tháo đường, bệnh bàn chân đái tháo đường, v.v.)
  * [Tạp chí thuộc Nature: mỗi ngày hai lạng Trung Quốc (100 gam) bông cải xanh, vừa khỏe mạnh vừa sống lâu! Phân tích dữ liệu trong 23 năm của gần 60 nghìn người cho thấy ăn thực phẩm chứa flavonoid có liên quan đến giảm 20% nguy cơ tử vong | Phát hiện lâm sàng lớn](https://mp.weixin.qq.com/s/E6BAi-Vnhr1jXBm0Pys2ZQ)
    * Nguồn: [Flavonoid intake is associated with lower mortality in the Danish Diet Cancer and Health Cohort](https://www.nature.com/articles/s41467-019-11622-x)
    * Ăn thực phẩm chứa flavonoid có liên quan đến giảm 20% nguy cơ tử vong
    * ![Flavonoid](https://user-images.githubusercontent.com/2707039/163703969-42e64f88-e727-4e7d-85f2-07a92e29b613.jpg)
    * Tiến sĩ Bondonno nói: “Ăn nhiều loại rau quả để bổ sung các loại hợp chất flavonoid khác nhau là rất quan trọng; điều này rất dễ thực hiện qua chế độ ăn: một tách trà, một quả táo, một quả cam, 100 gam việt quất hoặc 100 gam bông cải xanh có thể cung cấp nhiều loại hợp chất flavonoid với tổng hàm lượng trên 500 miligam.”
* Ớt
  * [Ớt trở thành khắc tinh của tử vong? Theo khảo sát, thường xuyên ăn cay có thể giảm 61% nguy cơ tử vong do bệnh](https://3g.163.com/dy/article/F6Q7I1ME053228ZU.html)
    * Nguồn 1: [Chili pepper consumption and mortality in Italian adults](https://www.sciencedirect.com/science/article/pii/S0735109719382063)
	* Nguồn 2: [The Association of Hot Red Chili Pepper Consumption and Mortality: A Large Population-Based Cohort Study](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0169876)
    * Một nghiên cứu khác từ Hoa Kỳ trên Plos One năm 2017 khảo sát 16179 người trên 18 tuổi, theo dõi họ trong thời gian lên tới 19 năm, và ghi nhận 4946 trường hợp tử vong. Tỷ lệ tử vong do mọi nguyên nhân ở những người tham gia ăn ớt là 21.6％, còn ở những người không ăn ớt là 33.6％. So với nhóm không ăn cay hoặc ít ăn cay (ít hơn hai lần mỗi tuần), nhóm ăn cay ＞4 lần mỗi tuần có nguy cơ tử vong chung giảm 23% và nguy cơ tử vong do tim mạch giảm 34%.
* Trứng
  * [Ăn thêm nửa quả trứng mỗi ngày làm tăng 7% nguy cơ tử vong do mọi nguyên nhân và do tim mạch?](https://m.thepaper.cn/baijiahao_11540780)
    * Nguồn: [Trang chủ nghiên cứu NIH-AARP](https://dietandhealth.cancer.gov/)、[Egg and cholesterol consumption and mortality from cardiovascular and different causes in the United States: A population-based cohort study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7872242/)
    * Ăn thêm nửa quả trứng mỗi ngày làm tăng 7% nguy cơ tử vong do mọi nguyên nhân và do tim mạch? Trong phân tích thay thế giả định, các nhà nghiên cứu phát hiện rằng thay nửa quả trứng nguyên (25 gam/ngày) bằng lượng tương đương lòng trắng trứng/sản phẩm thay thế trứng, thịt gia cầm, cá, sản phẩm sữa, các loại hạt và các loại đậu có thể lần lượt giảm 6%, 8%, 9%, 7%, 13% và 10% tỷ lệ tử vong do mọi nguyên nhân.
	*[Trứng](https://raw.githubusercontent.com/qhy040404/Image-Resources-Repo/master/pmed.1003508.g002.jpg)
* Các loại hạt
  * [Nghiên cứu 20 năm của Harvard: người ăn quả óc chó sống lâu hơn, giảm đáng kể tử vong do mọi nguyên nhân, kéo dài tuổi thọ](https://www.163.com/dy/article/GKVOMMMF05148PF4.html)
    * Nguồn: [Association of Walnut Consumption with Total and Cause-Specific Mortality and Life Expectancy in US Adults](https://www.mdpi.com/2072-6643/13/8/2699/pdf)
    * Phân tích cho thấy thường xuyên ăn quả óc chó có thể kéo dài tuổi thọ và giảm nguy cơ tử vong do bệnh tim mạch. So với không ăn quả óc chó, ăn hơn 5 khẩu phần mỗi tuần (1 khẩu phần 28 gam) giúp tăng 1.3 năm tuổi thọ kỳ vọng khỏe mạnh, giảm 14% nguy cơ tử vong do mọi nguyên nhân và giảm 25% tỷ lệ tử vong do bệnh tim mạch.
  * [Nghiên cứu: ăn hạt sống hằng ngày giúp giảm 20% tỷ lệ tử vong](https://zhuanlan.zhihu.com/p/44454030)
    * Nguồn 1: [Association of nut consumption with total and cause-specific mortality](https://www.nejm.org/doi/full/10.1056/NEJMoa1307352)
    * Nguồn 2: [APG_Health-&-Nutrition-Research-Brochure_DEC-19-18](https://americanpistachios.cn/sites/china/files/inline-files/APG_Health-%26-Nutrition-Research-Brochure_DEC-19-18.pdf)
    * Các nhà nghiên cứu phát hiện rằng những người ăn dưới 1 ounce hạt cây mỗi tuần có tỷ lệ tử vong giảm 7%. Những người ăn 1 khẩu phần 1 ounce mỗi tuần giảm 11% tỷ lệ tử vong; người ăn 2 khẩu phần mỗi tuần giảm 13%; người ăn 5 đến 6 khẩu phần mỗi tuần giảm 15%; người ăn hơn 7 khẩu phần mỗi tuần giảm 20% tỷ lệ tử vong.
    * Hai bài nghiên cứu y học sơ bộ khác, đăng trên Public Library of Science Online Journal và BioMed Central, trình bày dữ liệu cắt ngang vào thời điểm bắt đầu thử nghiệm. Cả hai nghiên cứu đều đánh giá 7,216 đối tượng và mối liên hệ với tần suất, lượng hạt họ ăn. Những đối tượng ăn hơn ba khẩu phần hạt mỗi tuần (bao gồm hạt dẻ cười) có tỷ lệ tử vong giảm 39%.
* Natri (còn nhiều tranh cãi)
  * [Eur Heart J: mối liên hệ giữa lượng natri tiêu thụ với tuổi thọ kỳ vọng và tỷ lệ tử vong do mọi nguyên nhân](https://nursing.medsci.cn/article/show_article.do;jsessionid=A34E8A33918A152CB55BDD2E5FB1798D?id=afe720486ee7)
    * Nguồn: [Messerli F H, Hofstetter L, Syrogiannouli L, et al. Sodium intake, life expectancy, and all-cause mortality[J]. European heart journal, 2021, 42(21): 2103-2112.](https://europepmc.org/backend/ptpmcrender.fcgi?accid=PMC8169157&blobtype=pdf)
    * ![ehaa947f6](https://user-images.githubusercontent.com/2707039/164894778-9710f18d-e055-4f62-bdcb-618687771d77.jpeg)
    * Trong 181 quốc gia được đưa vào phân tích này, các nhà nghiên cứu phát hiện lượng natri tiêu thụ có tương quan thuận với tuổi thọ kỳ vọng khỏe mạnh khi sinh (β=2.6 năm/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.66, P<0.001) và tuổi thọ kỳ vọng khỏe mạnh ở tuổi 60 (β=0.3 năm/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.60, P=0.048), nhưng không liên quan đến tử vong do bệnh không lây nhiễm (β=17 biến cố/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.43, P=0.100). Ngược lại, tỷ lệ tử vong do mọi nguyên nhân có tương quan nghịch với lượng natri tiêu thụ (β=−131 biến cố/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.60, P<0.001). Trong phân tích độ nhạy chỉ giới hạn ở 46 quốc gia có thu nhập cao nhất, lượng natri tiêu thụ có tương quan thuận với tuổi thọ kỳ vọng khỏe mạnh khi sinh (β=3.4 năm/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.53, P<0.001), và tương quan nghịch với tỷ lệ tử vong do mọi nguyên nhân (β=−168 biến cố/gam natri tiêu thụ hằng ngày, R<sup>2</sup>=0.50, P<0.001).
    * Nghiên cứu (trên phạm vi rộng) này cho rằng lượng natri tiêu thụ cao hơn có liên quan đến tỷ lệ tử vong do mọi nguyên nhân thấp hơn đáng kể
    * [Diễn giải mở rộng và thảo luận về bài báo này: A Fresh Foray in the Salt Wars: Life Expectancy Higher With Greater Sodium Intake](https://www.tctmd.com/news/fresh-foray-salt-wars-life-expectancy-higher-greater-sodium-intake)
  * [NEJM/Lancet: đừng ăn quá nhiều muối; Trung Quốc đứng đầu thế giới về tử vong do bệnh tim mạch và ung thư liên quan đến chế độ ăn; ăn muối ít natri có thể giảm tỷ lệ tử vong do mọi nguyên nhân](https://ibook.antpedia.com/x/669028.html)
    * Tuy nhiên, nhiều nghiên cứu cũng cho rằng sử dụng muối ít natri có thể giảm xác suất mắc một loạt bệnh và có tác động tích cực đến việc giảm tỷ lệ tử vong do mọi nguyên nhân
* Carbohydrate (còn nhiều tranh cãi)
  * [Chế độ ăn ketogenic ít carbohydrate (phần bốn): carbohydrate và tỷ lệ tử vong dài hạn](https://zhuanlan.zhihu.com/p/137815934)
    * Nguồn: The Lancet Public Health - [Dietary carbohydrate intake and mortality: a prospective cohort study and meta-analysis](https://www.sciencedirect.com/science/article/pii/S246826671830135X)
    * Lượng carbohydrate càng thấp, tuổi thọ càng ngắn; lượng carbohydrate càng cao, tuổi thọ cũng giảm nhẹ; mức carbohydrate khoảng 50% (thực ra, theo cách gọi thông thường, mức này cũng được xem là nhiều carbohydrate) là khoảng có tuổi thọ dài nhất
    * ![Carbohydrate](https://user-images.githubusercontent.com/2707039/163703985-a2e2f8ac-101a-4f3c-903b-6850507f144b.jpg)
  * [Phối hợp dinh dưỡng tối ưu! BMJ: ăn thế này giúp giảm nguy cơ bệnh tim mạch và tử vong](https://www.chinacdc.cn/gwxx/202003/t20200323_214639.html)
* Cau
  * [Nên nhìn nhận thế nào về ung thư do nhai cau? Nguy cơ gây ung thư của cau lớn đến đâu? - Câu trả lời của Bác sĩ Đinh Hương - Zhihu](https://www.zhihu.com/question/312784161/answer/603370131)
    * Nguồn: Chewing Betel Quid and the Risk of Metabolic Disease, Cardiovascular Disease, and All-Cause Mortality: A Meta-Analysis(https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0070679)
    * Nhai cau làm tăng 21% tỷ lệ tử vong do mọi nguyên nhân
* Hạn chế calo
  * [Đánh giá thế nào về chương trình «Ăn uống, nhịn ăn và sống lâu» của BBC?](https://www.zhihu.com/question/31395511)
    * Thí nghiệm hạn chế calo trên động vật: CR (hạn chế calo, tức ăn ít hơn) trì hoãn sự khởi phát nhiều bệnh và tử vong ở khỉ rhesus; so với động vật áp dụng CR, khỉ được cho ăn bình thường có nguy cơ mắc các bệnh tăng 2.9 lần và nguy cơ tử vong tăng 3.0 lần.
    * ![Hạn chế calo-khỉ rhesus](https://user-images.githubusercontent.com/2707039/163703988-8767185b-326a-4783-b2e2-f190322bb7d6.jpg)
* Tổng hợp
  * [Phối hợp dinh dưỡng tối ưu! BMJ: ăn thế này giúp giảm nguy cơ bệnh tim mạch và tử vong](https://www.chinacdc.cn/gwxx/202003/t20200323_214639.html)
  * [Associations of fat and carbohydrate intake with cardiovascular disease and mortality: prospective cohort study of UK Biobank participants](https://doi.org/10.1136/bmj.m688)
    * Qua phân tích dữ liệu của những người tham gia này, các nhà nghiên cứu phát hiện lượng carbohydrate (đường, tinh bột và chất xơ) và protein tiêu thụ có mối liên hệ phi tuyến với tỷ lệ tử vong do mọi nguyên nhân, trong khi chất béo có tương quan tuyến tính với tỷ lệ tử vong do mọi nguyên nhân. Trong đó, lượng đường tiêu thụ cao hơn liên quan đến cả nguy cơ tử vong do mọi nguyên nhân cao hơn lẫn nguy cơ mắc bệnh tim mạch cao hơn, còn lượng axit béo bão hòa tiêu thụ cao hơn liên quan đến nguy cơ tử vong do mọi nguyên nhân cao hơn.
    * Hình 1: mối liên hệ giữa các chất dinh dưỡng và tử vong do mọi nguyên nhân
    * ![Mối liên hệ giữa các chất dinh dưỡng và tử vong do mọi nguyên nhân](https://user-images.githubusercontent.com/2707039/163702022-8c2bfea9-ed5d-4fe0-8ead-e8740014b92b.jpg)
    * Hình 2: mối liên hệ giữa các chất dinh dưỡng và bệnh tim mạch
    * ![Mối liên hệ giữa các chất dinh dưỡng và bệnh tim mạch](https://user-images.githubusercontent.com/2707039/163702084-97fb4a03-707c-475d-b88e-6fe2f8e87f92.jpg)
    * **Nghiên cứu sâu hơn cho thấy, trong tất cả các kiểu ăn uống, chế độ ăn có nguy cơ tử vong do mọi nguyên nhân thấp nhất gồm: 10-30g chất xơ, 14-30% protein, 10-25% axit béo không bão hòa đơn, 5%-7% axit béo không bão hòa đa và 20%-30% tinh bột.**
    * **Tỷ lệ nguồn năng lượng tối ưu: <24% tinh bột, 15%-17% protein, >15% axit béo không bão hòa đơn, <15% đường, 6% axit béo bão hòa, 6% axit béo không bão hòa đa, 30g+ chất xơ**
  * [BMJ | Thường xuyên ăn khoai tây lát chiên, hamburger, sô-cô-la và các thực phẩm tương tự: tuổi tử vong trung bình chỉ 58, nguy cơ tử vong tăng mạnh](https://med.ckcest.cn/details.html?id=5183272274855936&classesEn=news)
    * [Rico-Campà A, Martínez-González M A, Alvarez-Alvarez I, et al. Association between consumption of ultra-processed foods and all cause mortality: SUN prospective cohort study[J]. bmj, 2019, 365.](https://www.bmj.com/content/365/bmj.l1949.full)
    * [Srour B, Fezeu L K, Kesse-Guyot E, et al. Ultra-processed food intake and risk of cardiovascular disease: prospective cohort study (NutriNet-Santé)[J]. bmj, 2019, 365.](https://www.bmj.com/content/365/bmj.l1451)
    * [Lawrence M A, Baker P I. Ultra-processed food and adverse health outcomes[J]. bmj, 2019, 365.](https://www.researchgate.net/profile/Phillip-Baker-5/publication/333483796_Ultra-processed_food_and_adverse_health_outcomes/links/5f0c646ca6fdcc2f32336a95/Ultra-processed-food-and-adverse-health-outcomes.pdf)

##### 6.1.2. Chất lỏng

* Sữa bò
  * [The Lancet khảo sát 130 nghìn người ở 21 quốc gia: mỗi ngày 1 cân Trung Quốc (500 gam) sữa bò hoặc sữa chua, nguy cơ tử vong do tim mạch giảm 23%](https://www.sohu.com/a/253940257_419768)
  * Nguồn: [Association of dairy intake with cardiovascular disease and mortality in 21 countries from five continents (PURE): a prospective cohort study](http://mdrf-eprints.in/1114/1/Association_of_dietary_patterns_and_dietary_diversity_with_cardiometabolic_disease_risk_factors.pdf)
  * So với người không dùng sản phẩm sữa, người dùng hai khẩu phần sản phẩm sữa mỗi ngày (một khẩu phần là 244 gam sữa bò/sữa chua, 15 gam phô mai hoặc 5 gam bơ) có **nguy cơ tử vong do mọi nguyên nhân giảm 17%**, nguy cơ tử vong do tim mạch giảm 23% và nguy cơ đột quỵ giảm 33%
* Trà
  * [Theo dõi 100 nghìn người Trung Quốc trong 7 năm cho thấy uống trà ba lần mỗi tuần có liên quan đến giảm 15% nguy cơ tử vong do mọi nguyên nhân và tăng 1.26 năm tuổi thọ kỳ vọng ](https://www.jianshu.com/p/5461a205cf95?utm_campaign=hugo)
  * Nguồn: [Tea consumption and the risk of atherosclerotic cardiovascular disease and all-cause mortality: The China-PAR project](https://www.researchgate.net/profile/Fangchao-Liu-4/publication/338483323_Tea_consumption_and_the_risk_of_atherosclerotic_cardiovascular_disease_and_all-cause_mortality_The_China-PAR_project/links/5e55e5e94585152ce8efe511/Tea-consumption-and-the-risk-of-atherosclerotic-cardiovascular-disease-and-all-cause-mortality-The-China-PAR-project.pdf)
  * [Nghiên cứu tiến cứu về mối liên hệ giữa uống trà và nguy cơ tử vong ở người trưởng thành Trung Quốc](http://rs.yiigle.com/CN112338202202/1351516.htm)
  * Trong 438 443 đối tượng được đưa vào phân tích, tổng cộng có 34 661 trường hợp tử vong trong 11.1 năm theo dõi. So với người chưa từng uống trà, HR tử vong do mọi nguyên nhân (95%CI) của người hiện uống trà không hằng ngày và người uống hằng ngày lần lượt là 0.89 (0.86-0.91) và 0.92 (0.88-0.95). Phân tích theo giới cho thấy tác dụng bảo vệ của uống trà đối với nguy cơ tử vong do mọi nguyên nhân chủ yếu thấy ở nam giới (P tương tác<0.05)
* Đồ uống không đường (có vị ngọt)
  * [«Đồ uống không đường làm tăng 26 % nguy cơ tử vong», có đúng không?](https://www.zhihu.com/question/418598272/answer/1450648364)
    * So với người tham gia uống nước giải khát <1 cốc/tháng, người uống hỗn hợp các loại nước giải khát ≥1 cốc/ngày có nguy cơ tử vong tăng 18%, còn **uống nước giải khát có đường hoặc không đường làm tăng nguy cơ tử vong lần lượt 11% và 27%.**
    * ![Đồ uống](https://user-images.githubusercontent.com/2707039/163704346-e7d92e7f-eba5-4673-8f15-3a96782c2e32.png)
  * [Association Between Soft Drink Consumption and Mortality in 10 European Countries](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2749350)
* Đồ uống có đường
  * [Cola và trà sữa làm tăng tỷ lệ tử vong do mọi nguyên nhân tới 62%! Nước ép trái cây làm giảm miễn dịch, ảnh hưởng chuyển hóa ở gan! Những điều về đồ uống có đường](https://zhuanlan.zhihu.com/p/400746073)
    * Mỗi ngày 1 cốc đồ uống có đường làm tăng 7% tỷ lệ tử vong do mọi nguyên nhân, 2 cốc tăng 21%
    * Trong 34 năm theo dõi, các nhà nghiên cứu phát hiện rằng so với những người uống 1 cốc đồ uống có đường hoặc ít hơn mỗi tháng, người uống 2 cốc mỗi ngày có nguy cơ tử vong chung tăng 21%, nguy cơ tử vong do bệnh tim mạch tăng 31% và nguy cơ tử vong do ung thư tăng 16%.
    * Chỉ cần uống thêm một cốc đồ uống có đường mỗi ngày, nguy cơ tử vong chung sẽ tăng 7%, nguy cơ bệnh tim mạch tăng 10% và nguy cơ tử vong liên quan đến ung thư tăng 16%.
    * Một bài báo đăng trên tạp chí hàng đầu quốc tế BMJ đã chứng minh rằng đồ uống có đường làm tăng nguy cơ mắc ung thư. Tất nhiên, bài báo không chỉ kiểm chứng nước ép trái cây, mà còn có cả trà sữa — nguy cơ mắc ung thư nói chung liên quan đến đồ uống có đường cao hơn mức thông thường 18%, và nước ép trái cây tươi 100% cũng làm tăng 12% nguy cơ mắc ung thư nói chung.
* Nước ép trái cây
  * [Tạp chí thuộc JAMA: nước ép trái cây nguyên chất 100% có thể nguy hiểm hơn đồ uống có đường](https://zhuanlan.zhihu.com/p/66513350)
    * Mỗi ngày uống thêm một khẩu phần 12 ounce đồ uống có đường làm tăng 11% nguy cơ tử vong do mọi nguyên nhân;
    * Mỗi ngày uống thêm một khẩu phần 12 ounce nước ép trái cây làm tăng 24% nguy cơ tử vong do mọi nguyên nhân.
* Cà phê
  * [Tin đáng chú ý! Nhiều nghiên cứu xác nhận uống cà phê liên quan trực tiếp đến giảm tỷ lệ tử vong do mọi nguyên nhân trong dân số](https://news.bioon.com/article/6725420.html)
  * [Phổ biến khoa học | Thêm một lý do mới để uống cà phê: giảm tỷ lệ tử vong! ](https://www.sohu.com/a/439412995_100003595)
  * [Tiêu thụ cà phê và tử vong do mọi nguyên nhân, bệnh tim mạch và ung thư ở người trưởng thành vùng Địa Trung Hải](https://fanyi.pdf365.cn/help/249)
    * Trong phân tích gộp gần đây, nghiên cứu này bao gồm 40 nghiên cứu từ các quốc gia khác nhau với 3,852,651 đối tượng. Phân tích gộp cho thấy lượng cà phê tiêu thụ có mối liên hệ phi tuyến với tỷ lệ tử vong do mọi nguyên nhân, CVD và ung thư; tỷ lệ tử vong do ung thư thấp nhất khi uống hai cốc cà phê mỗi ngày (RR = 0.96), tỷ lệ tử vong do CVD thấp nhất khi uống 2.5 cốc mỗi ngày (RR= 0.83), tỷ lệ tử vong chung thấp nhất khi uống 3.5 cốc mỗi ngày (RR= 0.85), và khi lượng cà phê tiêu thụ tăng, tỷ lệ tử vong không giảm thêm hoặc tăng thêm
* Spermidine
  * [Science: được khoa học chứng thực! Spermidine được phát hiện trong tinh dịch lại có những tác dụng phi thường như chống lão hóa, chống ung thư, bảo vệ tim mạch và thần kinh, cải thiện béo phì và tiểu đường tuýp 2](https://www.medsci.cn/article/show_article.do?id=420d12904103)
  * [Lượng spermidine cao trong chế độ ăn làm giảm tỷ lệ tử vong](https://zhuanlan.zhihu.com/p/388942219)

##### 6.1.3. Chất khí

* Hút thuốc
  * [Ngay cả hút thuốc ở mức độ thấp cũng làm tăng nguy cơ tử vong!](https://www.medsci.cn/article/show_article.do?id=02ca2083319b)
    * Nghiên cứu phát hiện: trong 42 416 nam giới và 86 735 nữ giới (35-89 tuổi, trước đó không mắc bệnh), 18 985 nam giới (45%) và 18 072 nữ giới (21%) hiện hút thuốc, trong đó 33% nam giới hút thuốc và 39% nữ giới hút thuốc không hút hằng ngày. Có 8866 nam giới (21%) và 53 912 nữ giới (62%) chưa từng hút thuốc. Trong thời gian theo dõi, so với chưa từng hút thuốc, tỷ số nguy cơ tử vong do mọi nguyên nhân khi hút <10 điếu/ngày hoặc ≥10 điếu/ngày lần lượt là 1.17 (khoảng tin cậy 95% 1.10-1.25) và 1.54 (1.42-1.67). Tỷ số nguy cơ tương tự nhau bất kể tuổi hay giới. Những bệnh liên quan chặt chẽ nhất với hút thuốc hằng ngày là ung thư đường hô hấp, bệnh phổi tắc nghẽn mạn tính, bệnh đường tiêu hóa và bệnh mạch máu. Những người đã bỏ thuốc khi được tuyển vào nghiên cứu có tỷ lệ tử vong thấp hơn những người hiện hút thuốc hằng ngày.
    * Người hút thuốc giảm trung bình 11-12 năm tuổi thọ
  * [Cơ chế nào khiến hút thuốc gây nghiện? Hút thuốc có chừng mực vẫn có hại không?](https://www.zhihu.com/question/24846224/answer/1719798177)

##### 6.1.4. Ánh sáng

* Phơi nắng
  * [Mối liên hệ giữa phơi nắng và tỷ lệ tử vong; làm sao phơi nắng khoa học, an toàn?](https://zhuanlan.zhihu.com/p/76301306)
    * Một nghiên cứu kéo dài 26 năm tại Đan Mạch phát hiện rằng tiếp xúc với ánh nắng nhiều hơn có thể kéo dài tuổi thọ đáng kể; ngay cả những bệnh nhân mắc ung thư da do phơi nắng quá mức cũng có tuổi thọ trung bình cao hơn người bình thường 6 năm.

##### 6.1.5. Thuốc

* NMN
* Metformin
  * [Dành cho người tung hô metformin: Tôi chính là thần dược — metformin](https://zhuanlan.zhihu.com/p/419202902)
    * Metformin không chỉ có tác dụng bảo vệ trong nhiều loại khối u, bệnh tim mạch và đái tháo đường, mà còn cho thấy tác dụng nổi bật đối với béo phì, bệnh gan, bệnh thận và lão hóa.
  * [Tin tức “hóng chuyện” đáng tìm hiểu nhất về metformin năm 2020 — bảo vệ dạ dày, tăng cường trí não, chống lão hóa, phòng ung thư hay gây ung thư?](https://zhuanlan.zhihu.com/p/357807109)
  * [Metformin có thực sự thần kỳ đến vậy? Nghiên cứu tại Mỹ: người cha dùng metformin có thể khiến con bị dị tật](https://baijiahao.baidu.com/s?id=1729999374705305768)
  * ![Metformin](https://user-images.githubusercontent.com/2707039/163702325-5d427542-9ae5-4311-8979-d0d326a9832f.jpg)
  * Phản ứng bất lợi
    * Là thuốc đã được sử dụng gần một trăm năm, metformin có các phản ứng bất lợi đã được xác định rất rõ; thường gặp gồm: thiếu vitamin B12 (7%-17.4%), phản ứng bất lợi đường tiêu hóa (cao nhất 53%), mệt mỏi (9%), đau đầu (6%); các phản ứng bất lợi nghiêm trọng nhưng ít gặp bao gồm nhiễm toan lactic, tổn thương gan; cũng có nghiên cứu cho thấy thuốc có thể gây dị tật thai nhi
* Vitamin tổng hợp
  * [Uống vitamin tổng hợp có thể giảm nguy cơ ung thư 8%, các tác dụng khác không rõ rệt](https://health.qq.com/a/20121023/000026.htm)
* Glucosamine
  * [Thật kỳ diệu! Glucosamine giảm tỷ lệ tử vong do bệnh tim mạch 65%, hiệu quả tương đương tập thể dục thường xuyên](https://www.sohu.com/a/436372221_120873241)
  * Nghiên cứu mới nhất của Đại học West Virginia, Mỹ, phát hiện glucosamine (chondroitin) có thể giảm tỷ lệ tử vong do bệnh tim mạch 65%, giảm tỷ lệ tử vong chung 39%, hiệu quả tương đương việc duy trì tập thể dục thường xuyên
  * Nghiên cứu sử dụng dữ liệu Khảo sát Kiểm tra Sức khỏe và Dinh dưỡng Quốc gia (NHANES) từ năm 1999 đến năm 2010 của 16,686 người trưởng thành; thời gian theo dõi trung vị là 107 tháng, trong đó 648 người tham gia dùng đều đặn 500-1000 miligam glucosamine/chondroitin mỗi ngày trong hơn một năm.
* Spermidine
  * [Science: được khoa học chứng thực! Spermidine được phát hiện trong tinh dịch lại có những tác dụng thần kỳ như chống lão hóa, chống ung thư, bảo vệ tim mạch và thần kinh, cải thiện béo phì và đái tháo đường típ 2](https://www.medsci.cn/article/show_article.do?id=420d12904103)
  * Spermidine là polyamine dễ được hấp thu nhất qua đường ruột của con người. Nhiều thực phẩm chứa lượng lớn spermidine, chẳng hạn như ớt chuông xanh tươi, mầm lúa mì, súp lơ trắng, bông cải xanh, nấm và các loại phô mai; hàm lượng đặc biệt cao trong các sản phẩm từ đậu nành như natto, nấm hương và sầu riêng. Trong nghiên cứu này, các nhà nghiên cứu chọn 829 người tham gia ở độ tuổi 45-84 để theo dõi trong 20 năm, phân tích mối liên hệ tiềm tàng giữa lượng spermidine hấp thu qua chế độ ăn và tỷ lệ tử vong ở người.
  * Nghiên cứu phát hiện lượng spermidine hấp thu ở nữ giới cao hơn nam giới và đều giảm dần theo tuổi. Các nguồn spermidine chính là ngũ cốc nguyên hạt (chiếm 13.4%), táo và lê (chiếm 13.3%), salad (chiếm 9.8%), rau mầm (chiếm 7.3%) và khoai tây (chiếm 6.4%). Nghiên cứu chia người tham gia thành ba nhóm theo lượng spermidine hấp thu: nhóm thấp (<62.2 µmol / d), nhóm trung bình (62.2–79.8 µmol / d) và nhóm cao (> 79.8 µmol / d). Trong thời gian theo dõi, tổng cộng ghi nhận 341 ca tử vong, trong đó 137 ca do bệnh mạch máu, 94 ca do ung thư và 110 ca do nguyên nhân khác. Tỷ lệ tử vong thô được tính toán ở ba nhóm thấp, trung bình và cao lần lượt là 40.5%, 23.7% và 15.1%; những dữ liệu này cho thấy mối tương quan nghịch có ý nghĩa giữa lượng spermidine hấp thu và tỷ lệ tử vong do mọi nguyên nhân. Sau khi lần lượt hiệu chỉnh theo tuổi, giới tính và tỷ lệ calo, mối tương quan này vẫn có ý nghĩa.
* Tổng hợp
  * [Bài tổng quan chuyên sâu trên tạp chí thành viên của Nature: cách phát triển thuốc chống lão hóa](https://zhuanlan.zhihu.com/p/145495570)
  * ![Cách phát triển thuốc chống lão hóa](https://user-images.githubusercontent.com/2707039/163702474-205baeec-f0ce-4e8d-96a4-36efe47534de.jpg)

#### 6.2. Đầu ra

##### 6.2.1. Các môn thể thao dùng vợt

* [Môn thể thao nào có lợi nhất so với công sức bỏ ra? Tạp chí y khoa uy tín The Lancet đã đưa ra câu trả lời ](https://www.sohu.com/a/535581770_121124216)
  * Chơi các môn thể thao dùng vợt ba lần mỗi tuần, mỗi lần 45-60 phút, giảm ~47% tỷ lệ tử vong do mọi nguyên nhân
  * Cầu lông, bóng bàn, quần vợt đều được tính là các môn thể thao dùng vợt, nhưng do bối cảnh nghiên cứu mang tính phương Tây nên có thể chủ yếu nói đến quần vợt. Điều này ngầm cho thấy tập luyện toàn thân quan trọng hơn

##### 6.2.2. Vận động cường độ cao

* [Nghiên cứu mới: vận động cường độ cao 8 phút mỗi ngày có thể giảm nguy cơ tử vong do mọi nguyên nhân và bệnh tim](https://academic.oup.com/eurheartj/advance-article/doi/10.1093/eurheartj/ehac572/6771381)
  * Vận động cường độ cao 15-20 phút mỗi tuần giúp giảm 16-40% tỷ lệ tử vong do mọi nguyên nhân; khi thời gian vận động cường độ cao đạt 50-57 phút/tuần, tỷ lệ tử vong do mọi nguyên nhân có thể giảm hơn nữa. Những phát hiện này cho thấy tích lũy một lượng vận động cường độ cao tương đối ít qua các khoảng thời gian ngắn trong tuần có thể giảm nguy cơ sức khỏe.

##### 6.2.3. Đi bộ

* [Đi bộ giảm tỷ lệ tử vong do mọi nguyên nhân hơn 50%! Mỗi ngày đi bao nhiêu bước là phù hợp nhất? Nghiên cứu hơn 10 năm trên tạp chí thành viên của JAMA cho bạn câu trả lời](http://www.shcell.org/219/3571.html)
  * ![Đi bộ giảm tỷ lệ tử vong do mọi nguyên nhân](https://user-images.githubusercontent.com/2707039/163704147-afec1c79-799b-4db8-b547-1a2431d504c9.jpg)
  * Chú thích 1: tuổi trung bình của người tham gia nghiên cứu này là 45.2
  * Chú thích 2: số bước trung bình có liên quan đến nghề nghiệp; nghiên cứu này chỉ cho thấy mối tương quan, chưa có phân tích nhân quả sâu hơn

##### 6.2.4. Đánh răng

* [Nghiên cứu trên 500 nghìn người Trung Quốc xác nhận: đánh răng không đúng cách gây ung thư! Bệnh mạch máu cũng gia tăng!](https://www.cn-healthcare.com/articlewm/20211209/content-1293760.html)
  * Ở những người thường xuyên không đánh răng: nguy cơ ung thư, bệnh phổi tắc nghẽn mạn tính và xơ gan lần lượt tăng 9%, 12% và 25%; nguy cơ tử vong sớm tăng 25%.

##### 6.2.5. Tắm ngâm

* [Tắm thường xuyên giảm nguy cơ mắc bệnh tim mạch](https://www.cn-healthcare.com/article/20200326/content-533379.html)
  * So với tắm ngâm một đến hai lần mỗi tuần hoặc hoàn toàn không tắm ngâm, tắm nước nóng mỗi ngày có thể giảm 28% tổng nguy cơ bệnh tim mạch, giảm 26% tổng nguy cơ đột quỵ và giảm 46% nguy cơ xuất huyết não. Tần suất tắm bồn không liên quan đến việc tăng nguy cơ đột tử do tim.

##### 6.2.6. Làm việc nhà (nam giới cao tuổi)

* [Housework Reduces All-Cause and Cancer Mortality in Chinese Men](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0061529)
  * Sau 72 tuổi, nam giới làm việc nhà nặng mỗi tuần có thể giảm 29% tỷ lệ tử vong trung bình
  * Việc nhà nặng: hút bụi, chà sàn, lau sàn, lau rửa cửa sổ, rửa xe, di chuyển đồ đạc, chuyển bình gas, v.v.
  * Việc nhà nhẹ: phủi bụi, rửa bát, giặt quần áo bằng tay, là quần áo, phơi quần áo, nấu ăn, mua đồ dùng hằng ngày, v.v.

##### 6.2.7. Giấc ngủ

* [Dữ liệu của hơn 300 nghìn người châu Á: ngủ bao nhiêu giờ mỗi ngày có lợi nhất cho tuổi thọ?](https://med.sina.com/article_detail_103_1_105491.html)
  * Ở nam giới, so với thời lượng ngủ 7 giờ: thời lượng ngủ ≥10 giờ có liên quan đến nguy cơ tử vong do mọi nguyên nhân tăng 34%;
  * ![Giấc ngủ - nam](https://user-images.githubusercontent.com/2707039/163704166-226b7ebb-92ce-4753-a3e7-77a87652a104.jpg)
  * Ở nữ giới, so với thời lượng ngủ 7 giờ: thời lượng ngủ ≥10 giờ có liên quan đến nguy cơ tử vong do mọi nguyên nhân tăng 48%;
  * ![Giấc ngủ - nữ](https://user-images.githubusercontent.com/2707039/163704169-c5c715aa-7130-403b-b0d1-ec34fab094d8.png)
* [Đảo ngược nhận thức! Nghiên cứu Canada phát hiện: đi ngủ sớm có thể hại sức khỏe hơn thức khuya, vậy nên ngủ lúc mấy giờ?](https://www.thepaper.cn/newsDetail_forward_14461799)
  * Một kết luận là giờ đi ngủ có mối liên hệ chặt chẽ với tỷ lệ tử vong do mọi nguyên nhân; đi ngủ quá sớm và quá muộn đều ảnh hưởng đến sức khỏe, nhưng mức tăng tỷ lệ tử vong do mọi nguyên nhân khi ngủ sớm cao hơn mức tăng khi ngủ muộn: ngủ sớm làm tăng nguy cơ tử vong 43%, còn ngủ muộn làm tăng nguy cơ tử vong 15%.
  * Nghiên cứu khảo sát này vẫn còn nhiều hạn chế, chẳng hạn chưa trực tiếp chứng minh mối quan hệ giữa giờ đi ngủ và tử vong mà chỉ cho thấy mối tương quan; thời lượng ngủ được thống kê qua tự báo cáo của người tham gia nên dữ liệu chưa đủ khách quan

##### 6.2.8. Ngồi lâu

* [Báo cáo nghiên cứu khoa học về Hướng dẫn chế độ ăn uống cho cư dân Trung Quốc (2021)](https://www.chinanutri.cn/yyjkzxpt/yyjkkpzx/yytsg/zgjm/202103/P020210311486742870527.pdf)
  * Thời gian ngồi lâu và xem tivi có liên quan đến nguy cơ cao tử vong do mọi nguyên nhân, mắc bệnh tim mạch, ung thư và đái tháo đường típ 2, và là yếu tố nguy cơ độc lập. Mỗi khi thời gian ngồi lâu tăng thêm 1 giờ mỗi ngày, nguy cơ mắc bệnh tim mạch tăng 4%, ung thư tăng 1% và nguy cơ tử vong do mọi nguyên nhân tăng 3%. Ngưỡng thời gian ngồi lâu làm tăng nguy cơ tử vong do mọi nguyên nhân và tử vong do CVD là 6\~8h/d, ngưỡng thời gian xem tivi là 3\~4h/d.
* [Hướng dẫn của Tổ chức Y tế Thế giới về hoạt động thể chất và hành vi ít vận động](https://apps.who.int/iris/bitstream/handle/10665/337001/9789240014947-chi.pdf)

#### 6.3. Bối cảnh

##### 6.3.1. Cảm xúc

* [Sự bi quan có liên quan đến tỷ lệ tử vong do mọi nguyên nhân và do bệnh tim mạch cao hơn, nhưng sự lạc quan không có tác dụng bảo vệ](https://www.x-mol.com/paper/1288184397379059712/t?recommendPaper=1263704526086578176)
* [Pessimism is associated with greater all-cause and cardiovascular mortality, but optimism is not protective](https://www.nature.com/articles/s41598-020-69388-y?utm_source=xmol&utm_medium=affiliate&utm_content=meta&utm_campaign=DDCN_1_GL01_metadata_scirep)
  * Trong giai đoạn 1993-1995, một nghiên cứu song sinh về sức khỏe của người Úc trên 50 tuổi đã bao gồm Bài kiểm tra Định hướng Cuộc sống (LOT), trong đó có các mục về lạc quan và bi quan. Trung bình 20 năm sau, người tham gia được đối chiếu với thông tin tử vong từ Chỉ số Tử vong Quốc gia Úc. Trong số 2,978 người tham gia có nhiều điểm số khả dụng, 1,068 người đã tử vong. Phân tích sống còn kiểm tra mối liên hệ giữa các yếu tố lạc quan và điểm số bi quan với tỷ lệ tử vong do bất kỳ nguyên nhân nào, ung thư, bệnh tim mạch hoặc các nguyên nhân đã biết khác. Điểm số trên thang đo bi quan sau hiệu chỉnh theo tuổi có liên quan đến tỷ lệ tử vong do mọi nguyên nhân và do bệnh tim mạch (tỷ số nguy cơ cho mỗi đơn vị độ lệch chuẩn, khoảng tin cậy 95％ và giá trị p lần lượt là 1.134, 1.065–1.207, 8.85×10 –5 và 1.196, 1.045–1.368, 0.0093), nhưng không liên quan đến tử vong do ung thư. Điểm số lạc quan có tương quan yếu với điểm số bi quan (hệ số tương quan thứ hạng sau hiệu chỉnh theo tuổi = − 0.176), nhưng không có tương quan có ý nghĩa với tỷ lệ tử vong chung hoặc do từng nguyên nhân cụ thể. Quan hệ nhân quả ngược (bệnh gây ra sự bi quan) là không thể, vì trong trường hợp đó, cả bệnh tim mạch và ung thư đều sẽ gây ra sự bi quan.

##### 6.3.2. Giàu nghèo

* [Tạp chí thành viên của JAMA: chênh lệch giàu nghèo thực sự có thể ảnh hưởng đến tuổi thọ? Điều này có thể là thật!](https://www.cn-healthcare.com/articlewm/20210727/content-1246348.html)
  * Nghiên cứu sử dụng dữ liệu được thu thập lần đầu vào năm 1994-1996 và phân tích mối liên hệ giữa tài sản ròng và tuổi thọ bằng mô hình sống còn. Kết quả cho thấy tổng cộng có 5414 người tham gia, tuổi trung bình 46.7, trong đó có 2766 phụ nữ. Tài sản ròng cao hơn có liên quan đến nguy cơ tử vong thấp hơn. Đặc biệt, trong nhóm anh chị em ruột và sinh đôi (n = 2490), cũng quan sát thấy mối liên hệ tương tự giữa tài sản ròng cao hơn và tỷ lệ tử vong thấp hơn, cho thấy người có nhiều của cải hơn sống lâu hơn anh chị em ruột hoặc anh chị em sinh đôi có ít của cải hơn.

##### 6.3.3. Cân nặng

* [Tạp chí thành viên của JAMA: cần giảm cân sớm mới có thể giảm nguy cơ tử vong hiệu quả](https://www.chinacdc.cn/gwxx/202009/t20200904_218959.html)
  * Đánh giá nguy cơ tử vong khi giảm cân cho thấy, so với những người duy trì tình trạng béo phì, người trưởng thành giảm cân từ mức béo phì xuống thừa cân có tỷ lệ tử vong do mọi nguyên nhân giảm 54％ (tỷ số nguy cơ là 0.46); tuy nhiên, những người giảm từ thừa cân ở giai đoạn đầu tuổi trưởng thành xuống cân nặng bình thường trước tuổi trung niên không có nguy cơ tử vong giảm (tỷ số nguy cơ là 1.12).
  * ![Table3](https://raw.githubusercontent.com/qhy040404/Image-Resources-Repo/master/zoi200509t3_1596761185.02415.png)

##### 6.3.4. COVID-19

* [Magnitude, demographics and dynamics of the effect of the first wave of the COVID-19 pandemic on all-cause mortality in 21 industrialized countries](https://www.nature.com/articles/s41591-020-1112-0.pdf)
  * Vào thời điểm viết bản gốc, tỷ lệ tử vong do COVID-19 (Mỹ) vào khoảng 1.5%, tuổi thọ kỳ vọng bình quân giảm 2 năm
* [Nhìn nhận thế nào về tuyên bố của CDC Mỹ rằng số ca tử vong do COVID-19 đã bị đánh giá quá cao?](https://www.zhihu.com/question/510943670/answer/2308499719)
* [NVSS deaths](https://www.cdc.gov/nchs/nvss/deaths.htm)

Bản dịch tham khảo của giấy phép: [LICENSE_vi.md](LICENSE_vi.md). Văn bản [LICENSE](LICENSE) bằng tiếng Anh là bản áp dụng.
