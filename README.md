# foody_API_data
`all_districts_hcm/*.csv`: chứa thông tin quán ăn của từng quận trong 24 quận
`all_dist_vers_1.csv` (58k dòng): merge tất cả file trong all_districts_hcm/
`all_dist_vers_2.csv` (69k dòng): file của Lượng
`data_hcm.csv` (93670 dòng): concat all_dist_vers_1.csv & all_dist_vers_2.csv 
`DataComments.csv` (93670 dòng): file chứa các comment của 93670 quán
`data_hcm_final.csv` (93048 dòng): merge với bên cào web + lọc ra những quán ko còn hoạt động nữa. Đây là file đầu ra cuối cùng