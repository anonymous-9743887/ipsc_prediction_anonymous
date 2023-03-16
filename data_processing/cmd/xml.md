<!-- MarkdownTOC -->

- [csv_to_yolov5](#csv_to_yolov5_)
    - [ipsc-5_class       @ csv_to_yolov5](#ipsc_5_class___csv_to_yolov_5_)
    - [ext_reorg_roi       @ csv_to_yolov5](#ext_reorg_roi___csv_to_yolov_5_)
- [xml_to_csv](#xml_to_cs_v_)
    - [10k       @ xml_to_csv](#10k___xml_to_csv_)
    - [20k       @ xml_to_csv](#20k___xml_to_csv_)
    - [20k7_new       @ xml_to_csv](#20k7_new___xml_to_csv_)
    - [25k7_new       @ xml_to_csv](#25k7_new___xml_to_csv_)
        - [test_0709       @ 25k7_new/xml_to_csv](#test_0709___25k7_new_xml_to_cs_v_)
    - [cows       @ xml_to_csv](#cows___xml_to_csv_)
    - [horses       @ xml_to_csv](#horses___xml_to_csv_)
        - [horse_16       @ horses/xml_to_csv](#horse_16___horses_xml_to_cs_v_)
        - [horse_24       @ horses/xml_to_csv](#horse_24___horses_xml_to_cs_v_)
        - [horse_25       @ horses/xml_to_csv](#horse_25___horses_xml_to_cs_v_)
    - [bear       @ xml_to_csv](#bear___xml_to_csv_)
        - [bear_1_1       @ bear/xml_to_csv](#bear_1_1___bear_xml_to_cs_v_)
        - [bear_1_1_even_10       @ bear/xml_to_csv](#bear_1_1_even_10___bear_xml_to_cs_v_)
    - [bison       @ xml_to_csv](#bison___xml_to_csv_)
        - [bison_60_w       @ bison/xml_to_csv](#bison_60_w___bison_xml_to_csv_)
        - [bison_42_w       @ bison/xml_to_csv](#bison_42_w___bison_xml_to_csv_)
    - [elk       @ xml_to_csv](#elk___xml_to_csv_)
    - [airport       @ xml_to_csv](#airport___xml_to_csv_)
    - [highway       @ xml_to_csv](#highway___xml_to_csv_)
    - [coyote_10_5       @ xml_to_csv](#coyote_10_5___xml_to_csv_)
    - [coyote_b       @ xml_to_csv](#coyote_b___xml_to_csv_)
    - [p1_highway       @ xml_to_csv](#p1_highway___xml_to_csv_)
    - [prototype_1_vid       @ xml_to_csv](#prototype_1_vid___xml_to_csv_)
    - [1_in_10_8_class       @ xml_to_csv](#1_in_10_8_class___xml_to_csv_)
    - [1_in_2_all_static       @ xml_to_csv](#1_in_2_all_static___xml_to_csv_)
    - [ipsc-5_class       @ xml_to_csv](#ipsc_5_class___xml_to_csv_)
    - [ext_reorg_roi       @ xml_to_csv](#ext_reorg_roi___xml_to_csv_)
        - [g2_38_53       @ ext_reorg_roi/xml_to_csv](#g2_38_53___ext_reorg_roi_xml_to_csv_)
        - [g2_0_15       @ ext_reorg_roi/xml_to_csv](#g2_0_15___ext_reorg_roi_xml_to_csv_)
        - [g2_0_53       @ ext_reorg_roi/xml_to_csv](#g2_0_53___ext_reorg_roi_xml_to_csv_)
    - [mj_rocks       @ xml_to_csv](#mj_rocks___xml_to_csv_)
    - [db4       @ xml_to_csv](#db4___xml_to_csv_)
        - [rockmaps       @ db4/xml_to_csv](#rockmaps___db4_xml_to_csv_)
- [csv_to_xml](#csv_to_xm_l_)
    - [db3_2_to_17_except_6_with_syn       @ csv_to_xml](#db3_2_to_17_except_6_with_syn___csv_to_xml_)
        - [large,huge       @ db3_2_to_17_except_6_with_syn/csv_to_xml](#large_huge___db3_2_to_17_except_6_with_syn_csv_to_xml_)
    - [part5_on_september_5_2020       @ csv_to_xml](#part5_on_september_5_2020___csv_to_xml_)
        - [large,huge       @ part5_on_september_5_2020/csv_to_xml](#large_huge___part5_on_september_5_2020_csv_to_xml_)
    - [part4_on_part5_on_september_5_2020       @ csv_to_xml](#part4_on_part5_on_september_5_2020___csv_to_xml_)
        - [large,huge       @ part4_on_part5_on_september_5_2020/csv_to_xml](#large_huge___part4_on_part5_on_september_5_2020_csv_to_xm_l_)
    - [part14_on_part4_on_part5_on_september_5_2020       @ csv_to_xml](#part14_on_part4_on_part5_on_september_5_2020___csv_to_xml_)
        - [large,huge       @ part14_on_part4_on_part5_on_september_5_2020/csv_to_xml](#large_huge___part14_on_part4_on_part5_on_september_5_2020_csv_to_xm_l_)
    - [db4_rockmaps_syn       @ csv_to_xml](#db4_rockmaps_syn___csv_to_xml_)
- [cvat_to_xml](#cvat_to_xml_)
    - [db4       @ cvat_to_xml](#db4___cvat_to_xm_l_)
        - [rockmaps       @ db4/cvat_to_xml](#rockmaps___db4_cvat_to_xm_l_)
    - [db3       @ cvat_to_xml](#db3___cvat_to_xm_l_)
        - [large,huge       @ db3/cvat_to_xml](#large_huge___db3_cvat_to_xm_l_)
    - [part4       @ cvat_to_xml](#part4___cvat_to_xm_l_)
    - [db3_2_to_17_except_6       @ cvat_to_xml](#db3_2_to_17_except_6___cvat_to_xm_l_)
        - [large,huge       @ db3_2_to_17_except_6/cvat_to_xml](#large_huge___db3_2_to_17_except_6_cvat_to_xml_)
    - [db3_2_to_17_except_6_with_syn       @ cvat_to_xml](#db3_2_to_17_except_6_with_syn___cvat_to_xm_l_)
        - [large,huge       @ db3_2_to_17_except_6_with_syn/cvat_to_xml](#large_huge___db3_2_to_17_except_6_with_syn_cvat_to_xm_l_)
    - [db3_2_to_17_except_6_no_rocks       @ cvat_to_xml](#db3_2_to_17_except_6_no_rocks___cvat_to_xm_l_)
        - [large,huge       @ db3_2_to_17_except_6_no_rocks/cvat_to_xml](#large_huge___db3_2_to_17_except_6_no_rocks_cvat_to_xm_l_)
    - [september_5_2020       @ cvat_to_xml](#september_5_2020___cvat_to_xm_l_)
        - [large,huge       @ september_5_2020/cvat_to_xml](#large_huge___september_5_2020_cvat_to_xml_)
    - [db3_syn       @ cvat_to_xml](#db3_syn___cvat_to_xm_l_)
        - [large,huge       @ db3_syn/cvat_to_xml](#large_huge___db3_syn_cvat_to_xm_l_)
    - [all       @ cvat_to_xml](#all___cvat_to_xm_l_)
        - [large,huge       @ all/cvat_to_xml](#large_huge___all_cvat_to_xm_l_)
    - [september_5_2020_2K_100       @ cvat_to_xml](#september_5_2020_2k_100___cvat_to_xm_l_)
        - [large,huge       @ september_5_2020_2K_100/cvat_to_xml](#large_huge___september_5_2020_2k_100_cvat_to_xm_l_)
    - [part1       @ cvat_to_xml](#part1___cvat_to_xm_l_)
        - [large,huge       @ part1/cvat_to_xml](#large_huge___part1_cvat_to_xm_l_)

<!-- /MarkdownTOC -->


<a id="csv_to_yolov5_"></a>
# csv_to_yolov5
<a id="ipsc_5_class___csv_to_yolov_5_"></a>
## ipsc-5_class       @ csv_to_yolov5-->xml
python36 csv_to_yolov5.py root_dir=/data/ipsc_5_class_raw class_names_path=data/predefined_classes_ipsc_5_class.txt

<a id="ext_reorg_roi___csv_to_yolov_5_"></a>
## ext_reorg_roi       @ csv_to_yolov5-->xml
python csv_to_yolov5.py root_dir=/data/ipsc/well3/images class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt enable_mask=1 ignore_invalid_class=1 consolidate_db=1

<a id="xml_to_cs_v_"></a>
# xml_to_csv
python xml_to_csv.py base_path=N:\Datasets\Acamp\marcin_180613\images seq_name=static_1

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\marcin_180615\list.txt" class_names_path=../labelling_tool/data/predefined_classes_orig.txt

python3 xml_to_csv.py root_dir="N:\Datasets\Acamp\test_data_annotations" class_names_path=../labelling_tool/data/predefined_classes_orig.txt

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\marcin_180613\images\deer\deer_2_5m" class_names_path=../labelling_tool/data/predefined_classes_orig.txt

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\acamp20k/deer_jesse_7_4" class_names_path=../labelling_tool/data/predefined_classes_orig.txt

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\backgrounds" class_names_path=../labelling_tool/data/predefined_classes_bkg.txt

<a id="10k___xml_to_csv_"></a>
## 10k       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=N:\Datasets\Acamp\acamp10k\animals class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\acamp10k\test\images\moose_21_1" class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths="N:\Datasets\Acamp\acamp10k\test\images\moose_21_1" class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths=../tf_api/acamp_all_bear.txt root_dir=/data/acamp/acamp20k/bear class_names_path=../labelling_tool/data/predefined_classes_10k.txt

<a id="20k___xml_to_csv_"></a>
## 20k       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=N:\Datasets\Acamp\acamp20k class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths=../tf_api/acamp20k_test_180719.txt root_dir=N:\Datasets\Acamp\acamp20k class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths=../tf_api/acamp20k_test_180720.txt root_dir=N:\Datasets\Acamp\acamp20k class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths=../tf_api/acamp20k_test_180720.txt root_dir=N:\Datasets\Acamp\acamp20k class_names_path=../labelling_tool/data/predefined_classes_10k.txt

python3 xml_to_csv.py seq_paths=../tf_api/acamp20k_test_180727.txt root_dir=N:\Datasets\Acamp\acamp20k class_names_path=../labelling_tool/data/predefined_classes_10k.txt

<a id="20k7_new___xml_to_csv_"></a>
## 20k7_new       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=../tf_api/acamp20k7_new_train.txt root_dir=/data/acamp/acamp20k class_names_path=../labelling_tool/data/predefined_classes_20k7.txt

<a id="25k7_new___xml_to_csv_"></a>
## 25k7_new       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=../tf_api/acamp25k7_train_new.txt root_dir=/data/acamp/acamp20k class_names_path=../labelling_tool/data/predefined_classes_20k7.txt

<a id="test_0709___25k7_new_xml_to_cs_v_"></a>
### test_0709       @ 25k7_new/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=acamp20k_test_0709.txt class_names_path=../labelling_tool/data/predefined_classes_10k.txt root_dir=N:\Datasets\Acamp\acamp20k

python3 xml_to_csv.py seq_paths=acamp20k_test_0709.txt class_names_path=../labelling_tool/data/predefined_classes_10k.txt  root_dir=/data/acamp/acamp20k

<a id="cows___xml_to_csv_"></a>
## cows       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=acamp_cows.txt class_names_path=../labelling_tool/data/predefined_classes_cow.txt root_dir=/data/acamp/acamp20k

<a id="horses___xml_to_csv_"></a>
## horses       @ xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=acamp_horses.txt class_names_path=../labelling_tool/data/predefined_classes_horse.txt root_dir=/data/acamp/acamp20k

<a id="horse_16___horses_xml_to_cs_v_"></a>
### horse_16       @ horses/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=horse_16 class_names_path=../labelling_tool/data/predefined_classes_horse.txt root_dir=/data/acamp/acamp20k

<a id="horse_24___horses_xml_to_cs_v_"></a>
### horse_24       @ horses/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=horse_24 class_names_path=../labelling_tool/data/predefined_classes_horse.txt root_dir=/data/acamp/acamp20k

<a id="horse_25___horses_xml_to_cs_v_"></a>
### horse_25       @ horses/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=horse_25 class_names_path=../labelling_tool/data/predefined_classes_horse.txt root_dir=/data/acamp/acamp20k

<a id="bear___xml_to_csv_"></a>
## bear       @ xml_to_csv-->xml
<a id="bear_1_1___bear_xml_to_cs_v_"></a>
### bear_1_1       @ bear/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=bear_1_1 class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k enable_mask=1

<a id="bear_1_1_even_10___bear_xml_to_cs_v_"></a>
### bear_1_1_even_10       @ bear/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=bear_1_1_even_10 class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/bear

<a id="bison___xml_to_csv_"></a>
## bison       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/bison

<a id="bison_60_w___bison_xml_to_csv_"></a>
### bison_60_w       @ bison/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=bison_60_w class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/bison

<a id="bison_42_w___bison_xml_to_csv_"></a>
### bison_42_w       @ bison/xml_to_csv-->xml
python3 xml_to_csv.py seq_paths=bison_42_w class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/bison

<a id="elk___xml_to_csv_"></a>
## elk       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/elk

<a id="airport___xml_to_csv_"></a>
## airport       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes_bear.txt seq_paths=/data/acamp/acamp20k/backgrounds\airport

<a id="highway___xml_to_csv_"></a>
## highway       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes_bear.txt seq_paths=/data/acamp/acamp20k/backgrounds\highway

<a id="coyote_10_5___xml_to_csv_"></a>
## coyote_10_5       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt seq_paths=/data/acamp/acamp20k/coyote\coyote_10_5

<a id="coyote_b___xml_to_csv_"></a>
## coyote_b       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt seq_paths=/data/acamp/acamp20k/coyote\coyote_b

<a id="p1_highway___xml_to_csv_"></a>
## p1_highway       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/prototype_1

<a id="prototype_1_vid___xml_to_csv_"></a>
## prototype_1_vid       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes.txt root_dir=/data/acamp/acamp20k/prototype_1_vid

<a id="1_in_10_8_class___xml_to_csv_"></a>
## 1_in_10_8_class       @ xml_to_csv-->xml
python3 xml_to_csv.py class_names_path=../labelling_tool/data/predefined_classes_4k8.txt root_dir=/data/acamp/acamp20k load_samples=1 load_samples_root=/data/acamp/acamp20k/1_in_10_8_class seq_paths=../tf_api/acamp_all_8_class.txt

<a id="1_in_2_all_static___xml_to_csv_"></a>
## 1_in_2_all_static       @ xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/acamp/acamp20k load_samples=1 load_samples_root=/data/acamp/acamp20k/1_in_2_all_static seq_paths=../tf_api/acamp_static_3_class.txt

<a id="ipsc_5_class___xml_to_csv_"></a>
## ipsc-5_class       @ xml_to_csv-->xml
python36 xml_to_csv.py root_dir=/data/ipsc_5_class_raw class_names_path=data/predefined_classes_ipsc_5_class.txt enable_mask=1

<a id="ext_reorg_roi___xml_to_csv_"></a>
## ext_reorg_roi       @ xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt enable_mask=1 csv_name=annotations.csv

<a id="g2_38_53___ext_reorg_roi_xml_to_csv_"></a>
### g2_38_53       @ ext_reorg_roi/xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt enable_mask=1 start_id=38 end_id=53 csv_name=annotations_38_53.csv

<a id="g2_0_15___ext_reorg_roi_xml_to_csv_"></a>
### g2_0_15       @ ext_reorg_roi/xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt enable_mask=1 start_id=0 end_id=15 csv_name=annotations_0_15.csv

<a id="g2_0_53___ext_reorg_roi_xml_to_csv_"></a>
### g2_0_53       @ ext_reorg_roi/xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt enable_mask=1 start_id=0 end_id=53 csv_name=annotations_0_53.csv

<a id="mj_rocks___xml_to_csv_"></a>
## mj_rocks       @ xml_to_csv-->xml
<a id="db4___xml_to_csv_"></a>
## db4       @ xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/mojow_rock/rock_dataset4 seq_paths=db4.txt enable_mask=1 csv_name=annotations.csv

<a id="rockmaps___db4_xml_to_csv_"></a>
### rockmaps       @ db4/xml_to_csv-->xml
python3 xml_to_csv.py root_dir=/data/mojow_rock/rock_dataset4/rockmaps seq_paths=db4.txt enable_mask=1 csv_name=annotations.csv recursive=1

<a id="csv_to_xm_l_"></a>
# csv_to_xml
<a id="db3_2_to_17_except_6_with_syn___csv_to_xml_"></a>
## db3_2_to_17_except_6_with_syn       @ csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=db3_2_to_17_except_6_with_syn.txt root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1

<a id="large_huge___db3_2_to_17_except_6_with_syn_csv_to_xml_"></a>
### large,huge       @ db3_2_to_17_except_6_with_syn/csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=db3_2_to_17_except_6_with_syn.txt root_dir=/data/mojow_rock/rock_dataset3  sizes=large,huge allow_missing_images=1

<a id="part5_on_september_5_2020___csv_to_xml_"></a>
## part5_on_september_5_2020       @ csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 allow_missing_images=0

<a id="large_huge___part5_on_september_5_2020_csv_to_xml_"></a>
### large,huge       @ part5_on_september_5_2020/csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 sizes=large,huge allow_missing_images=0

<a id="part4_on_part5_on_september_5_2020___csv_to_xml_"></a>
## part4_on_part5_on_september_5_2020       @ csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part4_on_part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 allow_missing_images=0

<a id="large_huge___part4_on_part5_on_september_5_2020_csv_to_xm_l_"></a>
### large,huge       @ part4_on_part5_on_september_5_2020/csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part4_on_part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 sizes=large,huge allow_missing_images=0

<a id="part14_on_part4_on_part5_on_september_5_2020___csv_to_xml_"></a>
## part14_on_part4_on_part5_on_september_5_2020       @ csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part14_on_part4_on_part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 allow_missing_images=0

<a id="large_huge___part14_on_part4_on_part5_on_september_5_2020_csv_to_xm_l_"></a>
### large,huge       @ part14_on_part4_on_part5_on_september_5_2020/csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=syn/part14_on_part4_on_part5_on_september_5_2020 root_dir=/data/mojow_rock/rock_dataset3 sizes=large,huge allow_missing_images=0

<a id="db4_rockmaps_syn___csv_to_xml_"></a>
## db4_rockmaps_syn       @ csv_to_xml-->xml
python3 -m csv_to_xml csv_paths=rockmaps/syn/part2_on_camera_stick_cs210422100/annotations.csv root_dir=/data/mojow_rock/rock_dataset4/ allow_missing_images=0

python3 -m csv_to_xml csv_paths=rockmaps/syn/part2_on_camera_stick_cs210422102/annotations.csv root_dir=/data/mojow_rock/rock_dataset4/ allow_missing_images=0

python3 -m csv_to_xml csv_paths=rockmaps/syn/part2_on_hub_cs210422100/annotations.csv root_dir=/data/mojow_rock/rock_dataset4/ allow_missing_images=0

python3 -m csv_to_xml csv_paths=rockmaps/syn/part2_on_hub_cs210422102/annotations.csv root_dir=/data/mojow_rock/rock_dataset4/ allow_missing_images=0

<a id="cvat_to_xml_"></a>
# cvat_to_xml
<a id="db4___cvat_to_xm_l_"></a>
## db4       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=db4.txt root_dir=/data/mojow_rock/rock_dataset4 allow_missing_images=0 move_images=0 vert_flip=1
<a id="rockmaps___db4_cvat_to_xm_l_"></a>
### rockmaps       @ db4/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db4.txt root_dir=/data/mojow_rock/rock_dataset4/rockmaps allow_missing_images=0 move_images=0 vert_flip=1 write_img=0 allow_missing_ann=1 write_empty=0

<a id="db3___cvat_to_xm_l_"></a>
## db3       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3.txt root_dir=/data/mojow_rock/rock_dataset3 allow_missing_images=1

<a id="large_huge___db3_cvat_to_xm_l_"></a>
### large,huge       @ db3/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3.txt root_dir=/data/mojow_rock/rock_dataset3 sizes=large,huge allow_missing_images=1

<a id="part4___cvat_to_xm_l_"></a>
## part4       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=part4 root_dir=/data/mojow_rock/rock_dataset3 allow_missing_images=1

<a id="db3_2_to_17_except_6___cvat_to_xm_l_"></a>
## db3_2_to_17_except_6       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6.txt root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1

<a id="large_huge___db3_2_to_17_except_6_cvat_to_xml_"></a>
### large,huge       @ db3_2_to_17_except_6/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6.txt root_dir=/data/mojow_rock/rock_dataset3  sizes=large,huge allow_missing_images=1

<a id="db3_2_to_17_except_6_with_syn___cvat_to_xm_l_"></a>
## db3_2_to_17_except_6_with_syn       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6_with_syn.txt root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1

<a id="large_huge___db3_2_to_17_except_6_with_syn_cvat_to_xm_l_"></a>
### large,huge       @ db3_2_to_17_except_6_with_syn/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6_with_syn.txt root_dir=/data/mojow_rock/rock_dataset3  sizes=large,huge allow_missing_images=1

<a id="db3_2_to_17_except_6_no_rocks___cvat_to_xm_l_"></a>
## db3_2_to_17_except_6_no_rocks       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6_no_rocks.txt root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1 write_empty=1 allow_missing_ann=1

<a id="large_huge___db3_2_to_17_except_6_no_rocks_cvat_to_xm_l_"></a>
### large,huge       @ db3_2_to_17_except_6_no_rocks/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_2_to_17_except_6_no_rocks.txt root_dir=/data/mojow_rock/rock_dataset3  sizes=large,huge allow_missing_images=1 write_empty=1 allow_missing_ann=1

<a id="september_5_2020___cvat_to_xm_l_"></a>
## september_5_2020       @ cvat_to_xml-->xml
python3 -m cvat_to_xml input=september_5_2020 root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1 write_empty=1 allow_target_id=0

<a id="large_huge___september_5_2020_cvat_to_xml_"></a>
### large,huge       @ september_5_2020/cvat_to_xml-->xml
python3 -m cvat_to_xml input=september_5_2020 root_dir=/data/mojow_rock/rock_dataset3  allow_missing_images=1 write_empty=1 sizes=large,huge

<a id="db3_syn___cvat_to_xm_l_"></a>
## db3_syn       @ cvat_to_xml-->xml
<a id="large_huge___db3_syn_cvat_to_xm_l_"></a>
### large,huge       @ db3_syn/cvat_to_xml-->xml
python3 -m cvat_to_xml input=db3_syn.txt root_dir=/data/mojow_rock/rock_dataset3  sizes=large,huge allow_missing_images=0

<a id="all___cvat_to_xm_l_"></a>
## all       @ cvat_to_xml-->xml
<a id="large_huge___all_cvat_to_xm_l_"></a>
### large,huge       @ all/cvat_to_xml-->xml
python3 -m cvat_to_xml input=/data/mojow_rock/rock_dataset3 sizes=large,huge

<a id="september_5_2020_2k_100___cvat_to_xm_l_"></a>
## september_5_2020_2K_100       @ cvat_to_xml-->xml
<a id="large_huge___september_5_2020_2k_100_cvat_to_xm_l_"></a>
### large,huge       @ september_5_2020_2K_100/cvat_to_xml-->xml
python3 -m cvat_to_xml --input=/data/mojow_rock/rock_dataset3/september_5_2020_2K_100/annotations.xml --output=/data/mojow_rock/rock_dataset3 --sizes=large,huge

<a id="part1___cvat_to_xm_l_"></a>
## part1       @ cvat_to_xml-->xml
<a id="large_huge___part1_cvat_to_xm_l_"></a>
### large,huge       @ part1/cvat_to_xml-->xml
python3 -m cvat_to_xml --input=/data/mojow_rock/rock_dataset3/part1/annotations.xml --output=/data/mojow_rock/rock_dataset3 --sizes=large,huge
