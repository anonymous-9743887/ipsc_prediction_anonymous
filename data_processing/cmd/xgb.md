<!-- MarkdownTOC -->

- [xgb       @ extract_cell_features](#xgb___extract_cell_feature_s_)
    - [all_frames_roi_g2_0_37       @ xgb](#all_frames_roi_g2_0_37___xg_b_)
    - [all_frames_roi_0_1_0_37       @ xgb](#all_frames_roi_0_1_0_37___xg_b_)
    - [ext_reorg_roi_g2_0_37       @ xgb](#ext_reorg_roi_g2_0_37___xg_b_)
    - [masked       @ xgb](#masked___xg_b_)
    - [ext_reorg_roi_g2_16_53       @ xgb](#ext_reorg_roi_g2_16_53___xg_b_)
        - [load-g2_54_126       @ ext_reorg_roi_g2_16_53/xgb](#load_g2_54_126___ext_reorg_roi_g2_16_53_xgb_)
        - [mask       @ ext_reorg_roi_g2_16_53/xgb](#mask___ext_reorg_roi_g2_16_53_xgb_)
    - [ext_reorg_roi_g2_54_126       @ xgb](#ext_reorg_roi_g2_54_126___xg_b_)
        - [on_g2_0_15       @ ext_reorg_roi_g2_54_126/xgb](#on_g2_0_15___ext_reorg_roi_g2_54_126_xg_b_)
- [swc       @ extract_cell_features](#swc___extract_cell_feature_s_)
    - [ext_reorg_roi_g2_0_37       @ swc](#ext_reorg_roi_g2_0_37___sw_c_)
        - [v1-base-224-1k       @ ext_reorg_roi_g2_0_37/swc](#v1_base_224_1k___ext_reorg_roi_g2_0_37_sw_c_)
        - [v1-large-384-22k       @ ext_reorg_roi_g2_0_37/swc](#v1_large_384_22k___ext_reorg_roi_g2_0_37_sw_c_)
        - [v2-base-256-1k       @ ext_reorg_roi_g2_0_37/swc](#v2_base_256_1k___ext_reorg_roi_g2_0_37_sw_c_)
    - [ext_reorg_roi_g2_0_37_masked       @ swc](#ext_reorg_roi_g2_0_37_masked___sw_c_)
    - [ext_reorg_roi_g2_16_53       @ swc](#ext_reorg_roi_g2_16_53___sw_c_)
    - [ext_reorg_roi_g2_54_126       @ swc](#ext_reorg_roi_g2_54_126___sw_c_)
        - [on_g2_0_15       @ ext_reorg_roi_g2_54_126/swc](#on_g2_0_15___ext_reorg_roi_g2_54_126_sw_c_)
- [cnx       @ extract_cell_features](#cnx___extract_cell_feature_s_)
    - [ext_reorg_roi_g2_0_37       @ cnx](#ext_reorg_roi_g2_0_37___cn_x_)
        - [large-384-22k       @ ext_reorg_roi_g2_0_37/cnx](#large_384_22k___ext_reorg_roi_g2_0_37_cn_x_)
        - [base-384-22k       @ ext_reorg_roi_g2_0_37/cnx](#base_384_22k___ext_reorg_roi_g2_0_37_cn_x_)
    - [ext_reorg_roi_g2_0_37_masked       @ cnx](#ext_reorg_roi_g2_0_37_masked___cn_x_)
        - [large-384-22k       @ ext_reorg_roi_g2_0_37_masked/cnx](#large_384_22k___ext_reorg_roi_g2_0_37_masked_cnx_)
    - [ext_reorg_roi_g2_16_53       @ cnx](#ext_reorg_roi_g2_16_53___cn_x_)
        - [large-384-22k       @ ext_reorg_roi_g2_16_53/cnx](#large_384_22k___ext_reorg_roi_g2_16_53_cnx_)
        - [base-384-22k       @ ext_reorg_roi_g2_16_53/cnx](#base_384_22k___ext_reorg_roi_g2_16_53_cnx_)
    - [ext_reorg_roi_g2_54_126       @ cnx](#ext_reorg_roi_g2_54_126___cn_x_)
        - [base-384-22k       @ ext_reorg_roi_g2_54_126/cnx](#base_384_22k___ext_reorg_roi_g2_54_126_cn_x_)
            - [on_g2_0_15       @ base-384-22k/ext_reorg_roi_g2_54_126/cnx](#on_g2_0_15___base_384_22k_ext_reorg_roi_g2_54_126_cnx_)
        - [large-384-22k       @ ext_reorg_roi_g2_54_126/cnx](#large_384_22k___ext_reorg_roi_g2_54_126_cn_x_)
            - [on_g2_0_15       @ large-384-22k/ext_reorg_roi_g2_54_126/cnx](#on_g2_0_15___large_384_22k_ext_reorg_roi_g2_54_126_cn_x_)

<!-- /MarkdownTOC -->

<a id="xgb___extract_cell_feature_s_"></a>
# xgb       @ extract_cell_features-->human
<a id="all_frames_roi_g2_0_37___xg_b_"></a>
## all_frames_roi_g2_0_37       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=37 val_ratio=0.3 allow_missing_images=0 description=all_frames_roi_g2_0_37 conf_thresholds=0:1:0.001

<a id="all_frames_roi_0_1_0_37___xg_b_"></a>
## all_frames_roi_0_1_0_37       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi_0_1.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=37 val_ratio=0.3 allow_missing_images=0 description=all_frames_roi_0_1_0_37

<a id="ext_reorg_roi_g2_0_37___xg_b_"></a>
## ext_reorg_roi_g2_0_37       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=0 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 end_id=-1 load=2 iw=1

<a id="masked___xg_b_"></a>
## masked       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=2 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 iw=0 end_id=-1 load=0 enable_mask=1 patch_border=0

<a id="ext_reorg_roi_g2_16_53___xg_b_"></a>
## ext_reorg_roi_g2_16_53       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=-16 allow_missing_images=0 description=ext_reorg_roi_g2_16_53 save_patches=0 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 load=2 iw=1

<a id="load_g2_54_126___ext_reorg_roi_g2_16_53_xgb_"></a>
### load-g2_54_126       @ ext_reorg_roi_g2_16_53/xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=-16 allow_missing_images=0 description=ext_reorg_roi_g2_16_53 save_patches=0 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 load=1 load_model=log/xgb/ext_reorg_roi_g2_54_126/xgb_trained.model iw=0

```
pix_vals_mean: [148.778, 148.778, 148.778]
pix_vals_std: [39.564, 39.564, 39.564]
```
__0_1__    
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi_0_1.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=54 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=0 ignore_invalid_label=1

<a id="mask___ext_reorg_roi_g2_16_53_xgb_"></a>
### mask       @ ext_reorg_roi_g2_16_53/xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=-16 allow_missing_images=0 description=ext_reorg_roi_g2_16_53 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 load=0 enable_mask=1 patch_border=0

<a id="ext_reorg_roi_g2_54_126___xg_b_"></a>
## ext_reorg_roi_g2_54_126       @ xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=126 n_val=-53 allow_missing_images=0 description=ext_reorg_roi_g2_54_126 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 load=1 load_model=1
```
pix_vals_mean: [141.945, 141.945, 141.945]
pix_vals_std: [39.812, 39.812, 39.812]
```
<a id="on_g2_0_15___ext_reorg_roi_g2_54_126_xg_b_"></a>
### on_g2_0_15       @ ext_reorg_roi_g2_54_126/xgb-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=126 n_val=-53 allow_missing_images=0 description=ext_reorg_roi_g2_54_126 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=0 load=1 test_dir=log/xgb/ext_reorg_roi_g2_54_126/on_g2_0_15 load_model=1 iw=1 n_val=16

<a id="swc___extract_cell_feature_s_"></a>
# swc       @ extract_cell_features-->human
<a id="ext_reorg_roi_g2_0_37___sw_c_"></a>
## ext_reorg_roi_g2_0_37       @ swc-->human
<a id="v1_base_224_1k___ext_reorg_roi_g2_0_37_sw_c_"></a>
### v1-base-224-1k       @ ext_reorg_roi_g2_0_37/swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_0_37-v1-base-224-1k/inference load=2 iw=1

<a id="v1_large_384_22k___ext_reorg_roi_g2_0_37_sw_c_"></a>
### v1-large-384-22k       @ ext_reorg_roi_g2_0_37/swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_0_37-v1-large-384-22k/inference load=2

<a id="v2_base_256_1k___ext_reorg_roi_g2_0_37_sw_c_"></a>
### v2-base-256-1k       @ ext_reorg_roi_g2_0_37/swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_0_37-v2-base-256-1k/inference load=2

<a id="ext_reorg_roi_g2_0_37_masked___sw_c_"></a>
## ext_reorg_roi_g2_0_37_masked       @ swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_0_37_masked save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_0_37_masked-v1-base-224-1k/inference load=2 iw=0

<a id="ext_reorg_roi_g2_16_53___sw_c_"></a>
## ext_reorg_roi_g2_16_53       @ swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_16_53 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_16_53-v1-base-224-1k/inference load=2 iw=0

<a id="ext_reorg_roi_g2_54_126___sw_c_"></a>
## ext_reorg_roi_g2_54_126       @ swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=15 allow_missing_images=0 description=ext_reorg_roi_g2_54_126 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_54_126-v1-base-224-1k/inference load=2 iw=0
<a id="on_g2_0_15___ext_reorg_roi_g2_54_126_sw_c_"></a>
### on_g2_0_15       @ ext_reorg_roi_g2_54_126/swc-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 n_val=16 allow_missing_images=0 description=ext_reorg_roi_g2_54_126 save_patches=1 ignore_invalid_label=1 conf_thresholds=0:1:0.001 get_img_stats=1 out_dir=log/swc/ext_reorg_roi_g2_54_126-v1-base-224-1k/on_g2_0_15/inference load=2 iw=1

<a id="cnx___extract_cell_feature_s_"></a>
# cnx       @ extract_cell_features-->human
<a id="ext_reorg_roi_g2_0_37___cn_x_"></a>
## ext_reorg_roi_g2_0_37       @ cnx-->human
<a id="large_384_22k___ext_reorg_roi_g2_0_37_cn_x_"></a>
### large-384-22k       @ ext_reorg_roi_g2_0_37/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_0_37 n_val=16 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_0_37-large-384-22k/checkpoint-242 load=2 iw=1

<a id="base_384_22k___ext_reorg_roi_g2_0_37_cn_x_"></a>
### base-384-22k       @ ext_reorg_roi_g2_0_37/cnx-->human
<a id="855___base_384_22k_ext_reorg_roi_g2_0_37_cnx_extract_cell_features_"></a>
__855__       @ base-384-22k/ext_reorg_roi_g2_0_37/cnx/extract_cell_features-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_0_37 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_0_37-base-384-22k/checkpoint-855 load=2 iw=0
<a id="856___base_384_22k_ext_reorg_roi_g2_0_37_cnx_extract_cell_features_"></a>
__856__       @ base-384-22k/ext_reorg_roi_g2_0_37/cnx/extract_cell_features-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_0_37 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_0_37-base-384-22k/checkpoint-856 load=2 iw=0
<a id="857___base_384_22k_ext_reorg_roi_g2_0_37_cnx_extract_cell_features_"></a>
__857__       @ base-384-22k/ext_reorg_roi_g2_0_37/cnx/extract_cell_features-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_0_37 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_0_37-base-384-22k/checkpoint-857 load=2 iw=0

<a id="ext_reorg_roi_g2_0_37_masked___cn_x_"></a>
## ext_reorg_roi_g2_0_37_masked       @ cnx-->human
<a id="large_384_22k___ext_reorg_roi_g2_0_37_masked_cnx_"></a>
### large-384-22k       @ ext_reorg_roi_g2_0_37_masked/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_0_37_masked conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_0_37_masked-large-384-22k/checkpoint-best load=2 iw=0

<a id="ext_reorg_roi_g2_16_53___cn_x_"></a>
## ext_reorg_roi_g2_16_53       @ cnx-->human
<a id="large_384_22k___ext_reorg_roi_g2_16_53_cnx_"></a>
### large-384-22k       @ ext_reorg_roi_g2_16_53/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_16_53 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_16_53-large-384-22k/checkpoint-247 n_val=16 load=2 iw=0
<a id="base_384_22k___ext_reorg_roi_g2_16_53_cnx_"></a>
### base-384-22k       @ ext_reorg_roi_g2_16_53/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_16_53 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_16_53-base-384-22k/checkpoint-1596 n_val=16 load=2 iw=0

<a id="ext_reorg_roi_g2_54_126___cn_x_"></a>
## ext_reorg_roi_g2_54_126       @ cnx-->human
<a id="base_384_22k___ext_reorg_roi_g2_54_126_cn_x_"></a>
### base-384-22k       @ ext_reorg_roi_g2_54_126/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_54_126 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_54_126-base-384-22k/checkpoint-1065 n_val=54 load=2 iw=0
<a id="on_g2_0_15___base_384_22k_ext_reorg_roi_g2_54_126_cnx_"></a>
#### on_g2_0_15       @ base-384-22k/ext_reorg_roi_g2_54_126/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_54_126 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_54_126-base-384-22k/on_g2_0_15/checkpoint-1065 n_val=16 load=2 iw=0

<a id="large_384_22k___ext_reorg_roi_g2_54_126_cn_x_"></a>
### large-384-22k       @ ext_reorg_roi_g2_54_126/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_54_126 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_54_126-large-384-22k/checkpoint-116 n_val=54 load=2 iw=0
<a id="on_g2_0_15___large_384_22k_ext_reorg_roi_g2_54_126_cn_x_"></a>
#### on_g2_0_15       @ large-384-22k/ext_reorg_roi_g2_54_126/cnx-->human
python3 extract_cell_features.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt allow_missing_images=0 description=ext_reorg_roi_g2_54_126 conf_thresholds=0:1:0.001 out_dir=log/cnx/ext_reorg_roi_g2_54_126-large-384-22k/on_g2_0_15/checkpoint-116 n_val=16 load=2 iw=1










