<!-- MarkdownTOC -->

- [ipsc](#ips_c_)
    - [all_frames_roi       @ ipsc](#all_frames_roi___ipsc_)
        - [swi       @ all_frames_roi/ipsc](#swi___all_frames_roi_ips_c_)
    - [ext_reorg_roi_0_37       @ ipsc](#ext_reorg_roi_0_37___ipsc_)
        - [swi       @ ext_reorg_roi_0_37/ipsc](#swi___ext_reorg_roi_0_37_ips_c_)
        - [no_validate-rcnn       @ ext_reorg_roi_0_37/ipsc](#no_validate_rcnn___ext_reorg_roi_0_37_ips_c_)
        - [no_validate-rcnn-win7       @ ext_reorg_roi_0_37/ipsc](#no_validate_rcnn_win7___ext_reorg_roi_0_37_ips_c_)
        - [rcnn-win7       @ ext_reorg_roi_0_37/ipsc](#rcnn_win7___ext_reorg_roi_0_37_ips_c_)
        - [cvnxt-large       @ ext_reorg_roi_0_37/ipsc](#cvnxt_large___ext_reorg_roi_0_37_ips_c_)
        - [cvnxt-large-coco       @ ext_reorg_roi_0_37/ipsc](#cvnxt_large_coco___ext_reorg_roi_0_37_ips_c_)
        - [cvnxt-base       @ ext_reorg_roi_0_37/ipsc](#cvnxt_base___ext_reorg_roi_0_37_ips_c_)
        - [idol       @ ext_reorg_roi_0_37/ipsc](#idol___ext_reorg_roi_0_37_ips_c_)
            - [idol-inc-sigma       @ idol/ext_reorg_roi_0_37/ipsc](#idol_inc_sigma___idol_ext_reorg_roi_0_37_ipsc_)
            - [idol-inc-probs       @ idol/ext_reorg_roi_0_37/ipsc](#idol_inc_probs___idol_ext_reorg_roi_0_37_ipsc_)
            - [idol-inc-all       @ idol/ext_reorg_roi_0_37/ipsc](#idol_inc_all___idol_ext_reorg_roi_0_37_ipsc_)
        - [seq       @ ext_reorg_roi_0_37/ipsc](#seq___ext_reorg_roi_0_37_ips_c_)
            - [seq-inc-sigma       @ seq/ext_reorg_roi_0_37/ipsc](#seq_inc_sigma___seq_ext_reorg_roi_0_37_ips_c_)
            - [seq-inc-probs       @ seq/ext_reorg_roi_0_37/ipsc](#seq_inc_probs___seq_ext_reorg_roi_0_37_ips_c_)
        - [vita-swin-inc       @ ext_reorg_roi_0_37/ipsc](#vita_swin_inc___ext_reorg_roi_0_37_ips_c_)
        - [vita-r50       @ ext_reorg_roi_0_37/ipsc](#vita_r50___ext_reorg_roi_0_37_ips_c_)
    - [ext_reorg_roi_16_53       @ ipsc](#ext_reorg_roi_16_53___ipsc_)
        - [yl8       @ ext_reorg_roi_16_53/ipsc](#yl8___ext_reorg_roi_16_53_ipsc_)
            - [val       @ yl8/ext_reorg_roi_16_53/ipsc](#val___yl8_ext_reorg_roi_16_53_ipsc_)
            - [seq-val       @ yl8/ext_reorg_roi_16_53/ipsc](#seq_val___yl8_ext_reorg_roi_16_53_ipsc_)
        - [swi       @ ext_reorg_roi_16_53/ipsc](#swi___ext_reorg_roi_16_53_ipsc_)
        - [swi-rcnn       @ ext_reorg_roi_16_53/ipsc](#swi_rcnn___ext_reorg_roi_16_53_ipsc_)
        - [cvnxt-large       @ ext_reorg_roi_16_53/ipsc](#cvnxt_large___ext_reorg_roi_16_53_ipsc_)
        - [idol       @ ext_reorg_roi_16_53/ipsc](#idol___ext_reorg_roi_16_53_ipsc_)
            - [probs       @ idol/ext_reorg_roi_16_53/ipsc](#probs___idol_ext_reorg_roi_16_53_ips_c_)
        - [idol-inc       @ ext_reorg_roi_16_53/ipsc](#idol_inc___ext_reorg_roi_16_53_ipsc_)
            - [probs       @ idol-inc/ext_reorg_roi_16_53/ipsc](#probs___idol_inc_ext_reorg_roi_16_53_ips_c_)
                - [nms-01       @ probs/idol-inc/ext_reorg_roi_16_53/ipsc](#nms_01___probs_idol_inc_ext_reorg_roi_16_53_ips_c_)
        - [seqformer       @ ext_reorg_roi_16_53/ipsc](#seqformer___ext_reorg_roi_16_53_ipsc_)
            - [probs       @ seqformer/ext_reorg_roi_16_53/ipsc](#probs___seqformer_ext_reorg_roi_16_53_ipsc_)
        - [seqformer-inc       @ ext_reorg_roi_16_53/ipsc](#seqformer_inc___ext_reorg_roi_16_53_ipsc_)
            - [probs       @ seqformer-inc/ext_reorg_roi_16_53/ipsc](#probs___seqformer_inc_ext_reorg_roi_16_53_ipsc_)
        - [vita       @ ext_reorg_roi_16_53/ipsc](#vita___ext_reorg_roi_16_53_ipsc_)
            - [0119999       @ vita/ext_reorg_roi_16_53/ipsc](#0119999___vita_ext_reorg_roi_16_53_ips_c_)
            - [0329999       @ vita/ext_reorg_roi_16_53/ipsc](#0329999___vita_ext_reorg_roi_16_53_ips_c_)
        - [vita-inc       @ ext_reorg_roi_16_53/ipsc](#vita_inc___ext_reorg_roi_16_53_ipsc_)
            - [0119999       @ vita-inc/ext_reorg_roi_16_53/ipsc](#0119999___vita_inc_ext_reorg_roi_16_53_ips_c_)
            - [0329999       @ vita-inc/ext_reorg_roi_16_53/ipsc](#0329999___vita_inc_ext_reorg_roi_16_53_ips_c_)
        - [vita-retrain-inc       @ ext_reorg_roi_16_53/ipsc](#vita_retrain_inc___ext_reorg_roi_16_53_ipsc_)
            - [0004999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc](#0004999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_)
            - [0079999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc](#0079999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_)
            - [0104999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc](#0104999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_)
    - [ext_reorg_roi_54_126       @ ipsc](#ext_reorg_roi_54_126___ipsc_)
        - [yl8       @ ext_reorg_roi_54_126/ipsc](#yl8___ext_reorg_roi_54_126_ips_c_)
            - [val       @ yl8/ext_reorg_roi_54_126/ipsc](#val___yl8_ext_reorg_roi_54_126_ips_c_)
            - [seq-val       @ yl8/ext_reorg_roi_54_126/ipsc](#seq_val___yl8_ext_reorg_roi_54_126_ips_c_)
        - [swi       @ ext_reorg_roi_54_126/ipsc](#swi___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_15       @ swi/ext_reorg_roi_54_126/ipsc](#g2_0_15___swi_ext_reorg_roi_54_126_ips_c_)
        - [cvnxt-base       @ ext_reorg_roi_54_126/ipsc](#cvnxt_base___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_15       @ cvnxt-base/ext_reorg_roi_54_126/ipsc](#g2_0_15___cvnxt_base_ext_reorg_roi_54_126_ipsc_)
        - [cvnxt-large       @ ext_reorg_roi_54_126/ipsc](#cvnxt_large___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_15       @ cvnxt-large/ext_reorg_roi_54_126/ipsc](#g2_0_15___cvnxt_large_ext_reorg_roi_54_126_ips_c_)
        - [idol-inc       @ ext_reorg_roi_54_126/ipsc](#idol_inc___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_15       @ idol-inc/ext_reorg_roi_54_126/ipsc](#g2_0_15___idol_inc_ext_reorg_roi_54_126_ipsc_)
        - [seqformer-inc       @ ext_reorg_roi_54_126/ipsc](#seqformer_inc___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_15       @ seqformer-inc/ext_reorg_roi_54_126/ipsc](#g2_0_15___seqformer_inc_ext_reorg_roi_54_126_ips_c_)
                - [max_length-2       @ g2_0_15/seqformer-inc/ext_reorg_roi_54_126/ipsc](#max_length_2___g2_0_15_seqformer_inc_ext_reorg_roi_54_126_ips_c_)
        - [vita       @ ext_reorg_roi_54_126/ipsc](#vita___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_53       @ vita/ext_reorg_roi_54_126/ipsc](#g2_0_53___vita_ext_reorg_roi_54_126_ipsc_)
                - [max_length-2       @ g2_0_53/vita/ext_reorg_roi_54_126/ipsc](#max_length_2___g2_0_53_vita_ext_reorg_roi_54_126_ipsc_)
            - [g2_0_15       @ vita/ext_reorg_roi_54_126/ipsc](#g2_0_15___vita_ext_reorg_roi_54_126_ipsc_)
                - [max_length-2       @ g2_0_15/vita/ext_reorg_roi_54_126/ipsc](#max_length_2___g2_0_15_vita_ext_reorg_roi_54_126_ipsc_)
        - [vita-inc       @ ext_reorg_roi_54_126/ipsc](#vita_inc___ext_reorg_roi_54_126_ips_c_)
            - [g2_0_53       @ vita-inc/ext_reorg_roi_54_126/ipsc](#g2_0_53___vita_inc_ext_reorg_roi_54_126_ipsc_)
                - [max_length-2       @ g2_0_53/vita-inc/ext_reorg_roi_54_126/ipsc](#max_length_2___g2_0_53_vita_inc_ext_reorg_roi_54_126_ipsc_)
            - [g2_0_15       @ vita-inc/ext_reorg_roi_54_126/ipsc](#g2_0_15___vita_inc_ext_reorg_roi_54_126_ipsc_)
                - [max_length-2       @ g2_0_15/vita-inc/ext_reorg_roi_54_126/ipsc](#max_length_2___g2_0_15_vita_inc_ext_reorg_roi_54_126_ipsc_)
- [mj_rocks](#mj_rock_s_)
    - [swi-db4       @ mj_rocks](#swi_db4___mj_rocks_)

<!-- /MarkdownTOC -->

<a id="ips_c_"></a>
# ipsc
<a id="all_frames_roi___ipsc_"></a>
## all_frames_roi       @ ipsc-->mAP

<a id="swi___all_frames_roi_ips_c_"></a>
### swi       @ all_frames_roi/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/all_frames_roi.txt det_paths=log/swi/ipsc_2_class_all_frames_roi_g2_0_37/g2_38_53/csv gt_csv_name=annotations_38_53.csv

<a id="ext_reorg_roi_0_37___ipsc_"></a>
## ext_reorg_roi_0_37       @ ipsc-->mAP
<a id="swi___ext_reorg_roi_0_37_ips_c_"></a>
### swi       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=swi gt_pkl=g2_38_53.pkl nms_thresh=0 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate/g2_38_53/csv gt_csv_name=annotations_38_53.csv  save_suffix=swi gt_pkl=g2_38_53.pkl n_proc=12 iw=1

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=swi gt_pkl=g2_38_53.pkl n_proc=12 iw=1 nms_thresh=0.1

<a id="no_validate_rcnn___ext_reorg_roi_0_37_ips_c_"></a>
### no_validate-rcnn       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-rcnn/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=swi-rcnn-no_validate gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12 enable_mask=0

<a id="no_validate_rcnn_win7___ext_reorg_roi_0_37_ips_c_"></a>
### no_validate-rcnn-win7       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-rcnn-win7/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=swi-rcnn-no_validate-win7 gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12 enable_mask=0

<a id="rcnn_win7___ext_reorg_roi_0_37_ips_c_"></a>
### rcnn-win7       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-rcnn-win7/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=swi-rcnn-win7 gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12 enable_mask=0

<a id="cvnxt_large___ext_reorg_roi_0_37_ips_c_"></a>
### cvnxt-large       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=cvnxt-large gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=cvnxt-large gt_pkl=g2_38_53.pkl iw=1

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=cvnxt-large gt_pkl=g2_38_53.pkl iw=1 nms_thresh=0.9

<a id="cvnxt_large_coco___ext_reorg_roi_0_37_ips_c_"></a>
### cvnxt-large-coco       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k_coco_pretrained/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=cvnxt-large-coco gt_pkl=g2_38_53.pkl

<a id="cvnxt_base___ext_reorg_roi_0_37_ips_c_"></a>
### cvnxt-base       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-convnext_base_in22k/g2_38_53/csv gt_csv_name=annotations_38_53.csv save_suffix=cvnxt-base gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12

<a id="idol___ext_reorg_roi_0_37_ips_c_"></a>
### idol       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/csv gt_csv_name=annotations_38_53.csv save_suffix=idol gt_pkl=g2_38_53.pkl

<a id="idol_inc_sigma___idol_ext_reorg_roi_0_37_ipsc_"></a>
#### idol-inc-sigma       @ idol/ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=idol-inc iw=0 gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12

<a id="idol_inc_probs___idol_ext_reorg_roi_0_37_ipsc_"></a>
#### idol-inc-probs       @ idol/ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_probs/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=idol-inc-probs iw=0 gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_probs/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=idol-inc-probs gt_pkl=g2_38_53.pkl iw=1

<a id="idol_inc_all___idol_ext_reorg_roi_0_37_ipsc_"></a>
#### idol-inc-all       @ idol/ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/csv gt_csv_name=annotations_38_53.csv save_suffix=idol-inc-all iw=0 end_id=0 gt_pkl=g2_38_53.pkl

<a id="seq___ext_reorg_roi_0_37_ips_c_"></a>
### seq       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference/csv gt_csv_name=annotations_38_53.csv save_suffix=seq gt_pkl=g2_38_53.pkl

<a id="seq_inc_sigma___seq_ext_reorg_roi_0_37_ips_c_"></a>
#### seq-inc-sigma       @ seq/ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=seq-inc gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=seq-inc n_proc=12 iw=1

<a id="seq_inc_probs___seq_ext_reorg_roi_0_37_ips_c_"></a>
#### seq-inc-probs       @ seq/ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_probs/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=seq-inc-probs gt_pkl=g2_38_53.pkl

<a id="vita_swin_inc___ext_reorg_roi_0_37_ips_c_"></a>
### vita-swin-inc       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_0_37_swin/inference_38_53-incremental/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=vita-swin-inc gt_pkl=g2_38_53.pkl nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_0_37_swin/inference_38_53-incremental/csv_incremental gt_csv_name=annotations_38_53.csv save_suffix=vita-swin-inc gt_pkl=g2_38_53.pkl n_proc=12 iw=1

<a id="vita_r50___ext_reorg_roi_0_37_ips_c_"></a>
### vita-r50       @ ext_reorg_roi_0_37/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_0_37_r50/inference/csv gt_csv_name=annotations_38_53.csv save_suffix=vita-r50 gt_pkl=g2_38_53.pkl

<a id="ext_reorg_roi_16_53___ipsc_"></a>
## ext_reorg_roi_16_53       @ ipsc-->mAP
<a id="yl8___ext_reorg_roi_16_53_ipsc_"></a>
### yl8       @ ext_reorg_roi_16_53/ipsc-->mAP
__last__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53/last/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-last gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__best__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53/best/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-best gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="val___yl8_ext_reorg_roi_16_53_ipsc_"></a>
#### val       @ yl8/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53-val/last/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-val-last gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53-val/best/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-val-best gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="seq_val___yl8_ext_reorg_roi_16_53_ipsc_"></a>
#### seq-val       @ yl8/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53-seq-val/last/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-seq-val-last gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.1 n_proc=1

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_16_53-seq-val/best/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-yl8-seq-val-best gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="swi___ext_reorg_roi_16_53_ipsc_"></a>
### swi       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_16_53-no_validate/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-swi gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_16_53-no_validate/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-swi gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 n_proc=12 iw=1

<a id="swi_rcnn___ext_reorg_roi_16_53_ipsc_"></a>
### swi-rcnn       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_16_53-no_validate-rcnn/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-swi-rcnn gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12 enable_mask=0

<a id="cvnxt_large___ext_reorg_roi_16_53_ipsc_"></a>
### cvnxt-large       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_16_53-convnext_large_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-cvnxt-large gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_16_53-convnext_large_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-cvnxt-large gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 n_proc=12 iw=1

<a id="idol___ext_reorg_roi_16_53_ipsc_"></a>
### idol       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-idol gt_pkl=g2_0_15.pkl

<a id="probs___idol_ext_reorg_roi_16_53_ips_c_"></a>
#### probs       @ idol/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_probs/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-probs gt_pkl=g2_0_15.pkl

<a id="idol_inc___ext_reorg_roi_16_53_ipsc_"></a>
### idol-inc       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-inc gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-inc iw=0 show_vis=0 show_tp=1 save_vis=0 n_proc=1 iw=1 gt_pkl=g2_0_15.pkl

<a id="probs___idol_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### probs       @ idol-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-inc-probs gt_pkl=g2_0_15.pkl nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-inc-probs gt_pkl=g2_0_15.pkl iw=1

<a id="nms_01___probs_idol_inc_ext_reorg_roi_16_53_ips_c_"></a>
##### nms-01       @ probs/idol-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental_probs/csv_incremental_nms_01 gt_csv_name=annotations_0_15.csv save_suffix=inv-idol-inc-probs-nms-01 gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 vid_fmt=H264,2,jpg

<a id="seqformer___ext_reorg_roi_16_53_ipsc_"></a>
### seqformer       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-seq gt_pkl=g2_0_15.pkl
<a id="probs___seqformer_ext_reorg_roi_16_53_ipsc_"></a>
#### probs       @ seqformer/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_probs/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-seq-probs gt_pkl=g2_0_15.pkl

<a id="seqformer_inc___ext_reorg_roi_16_53_ipsc_"></a>
### seqformer-inc       @ ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-seq-inc gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-seq-inc show_vis=0 show_tp=1 save_vis=0 iw=1 gt_pkl=g2_0_15.pkl

<a id="probs___seqformer_inc_ext_reorg_roi_16_53_ipsc_"></a>
#### probs       @ seqformer-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-seq-inc-probs gt_pkl=g2_0_15.pkl

<a id="vita___ext_reorg_roi_16_53_ipsc_"></a>
### vita       @ ext_reorg_roi_16_53/ipsc-->mAP
<a id="0119999___vita_ext_reorg_roi_16_53_ips_c_"></a>
#### 0119999       @ vita/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0119999/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-swin-0119999 gt_pkl=g2_0_15.pkl
<a id="0329999___vita_ext_reorg_roi_16_53_ips_c_"></a>
#### 0329999       @ vita/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999/csv gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-0329999 gt_pkl=g2_0_15.pkl

<a id="vita_inc___ext_reorg_roi_16_53_ipsc_"></a>
### vita-inc       @ ext_reorg_roi_16_53/ipsc-->mAP
<a id="0119999___vita_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### 0119999       @ vita-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0119999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-inc-0119999 gt_pkl=g2_0_15.pkl
<a id="0329999___vita_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### 0329999       @ vita-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-inc gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-inc gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 n_proc=12 iw=1

<a id="vita_retrain_inc___ext_reorg_roi_16_53_ipsc_"></a>
### vita-retrain-inc       @ ext_reorg_roi_16_53/ipsc-->mAP
<a id="0004999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### 0004999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0004999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-retrain-inc-0004999 gt_pkl=g2_0_15.pkl
<a id="0079999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### 0079999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0079999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-retrain-inc-0079999 gt_pkl=g2_0_15.pkl
<a id="0104999___vita_retrain_inc_ext_reorg_roi_16_53_ips_c_"></a>
#### 0104999       @ vita-retrain-inc/ext_reorg_roi_16_53/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0104999_incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=inv-vita-retrain-inc-0104999 gt_pkl=g2_0_15.pkl

<a id="ext_reorg_roi_54_126___ipsc_"></a>
## ext_reorg_roi_54_126       @ ipsc-->mAP
<a id="yl8___ext_reorg_roi_54_126_ips_c_"></a>
### yl8       @ ext_reorg_roi_54_126/ipsc-->mAP
__last__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126/last/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-last gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__best__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126/best/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-best gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="val___yl8_ext_reorg_roi_54_126_ips_c_"></a>
#### val       @ yl8/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126-val/last/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-val-last gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126-val/best/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-val-best gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="seq_val___yl8_ext_reorg_roi_54_126_ips_c_"></a>
#### seq-val       @ yl8/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126-seq-val/last/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-seq-val-last gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.1 n_proc=1

python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/yl8/ext_reorg_roi_g2_54_126-seq-val/best/csv gt_csv_name=annotations_0_53.csv save_suffix=inv-yl8-seq-val-best gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="swi___ext_reorg_roi_54_126_ips_c_"></a>
### swi       @ ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-no_validate/g2_0_53/csv gt_csv_name=annotations_0_53.csv save_suffix=full-swi iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12 gt_pkl=g2_0_53.pkl
<a id="g2_0_15___swi_ext_reorg_roi_54_126_ips_c_"></a>
#### g2_0_15       @ swi/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-no_validate/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-swi-g2_0_15 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1 gt_pkl=g2_0_15.pkl
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-no_validate/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-swi-g2_0_15 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.9 n_proc=1 gt_pkl=g2_0_15.pkl iw=1

<a id="cvnxt_base___ext_reorg_roi_54_126_ips_c_"></a>
### cvnxt-base       @ ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_base_in22k/g2_0_53/csv gt_csv_name=annotations_0_53.csv save_suffix=full-cvnxt-large gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="g2_0_15___cvnxt_base_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_15       @ cvnxt-base/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_base_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-cvnxt-large-g2_0_15 gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_base_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-cvnxt-large-g2_0_15 gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.9 n_proc=1 iw=1

<a id="cvnxt_large___ext_reorg_roi_54_126_ips_c_"></a>
### cvnxt-large       @ ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_large_in22k/g2_0_53/csv gt_csv_name=annotations_0_53.csv save_suffix=full-cvnxt-base gt_pkl=g2_0_53.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1
<a id="g2_0_15___cvnxt_large_ext_reorg_roi_54_126_ips_c_"></a>
#### g2_0_15       @ cvnxt-large/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_large_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-cvnxt-base-g2_0_15 gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_large_in22k/g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-cvnxt-base-g2_0_15 gt_pkl=g2_0_15.pkl iw=0 show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.9 n_proc=1 iw=1

<a id="idol_inc___ext_reorg_roi_54_126_ips_c_"></a>
### idol-inc       @ ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_incremental_probs/csv_incremental gt_csv_name=annotations_0_53.csv save_suffix=full-idol-inc-probs gt_pkl=g2_0_53.pkl nms_thresh=0:0.9:0.1 n_proc=12 
<a id="g2_0_15___idol_inc_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_15       @ idol-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_g2_0_15-incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-idol-inc-probs-g2_0_15 gt_pkl=g2_0_15.pkl nms_thresh=0:0.9:0.1 n_proc=1 
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_g2_0_15-incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-idol-inc-probs-g2_0_15 gt_pkl=g2_0_15.pkl nms_thresh=0.1 iw=1

<a id="seqformer_inc___ext_reorg_roi_54_126_ips_c_"></a>
### seqformer-inc       @ ext_reorg_roi_54_126/ipsc-->mAP
<a id="g2_0_15___seqformer_inc_ext_reorg_roi_54_126_ips_c_"></a>
#### g2_0_15       @ seqformer-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_g2_0_15-incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-seq-inc-g2_0_15 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_g2_0_15-incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-seq-inc-g2_0_15 show_vis=0 show_tp=1 save_vis=0 iw=1 gt_pkl=g2_0_15.pkl nms_thresh=0.9

<a id="max_length_2___g2_0_15_seqformer_inc_ext_reorg_roi_54_126_ips_c_"></a>
##### max_length-2       @ g2_0_15/seqformer-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_g2_0_15-max_length-2-incremental_probs/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-seq-inc-g2_0_15-max_length-2 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=1

<a id="vita___ext_reorg_roi_54_126_ips_c_"></a>
### vita       @ ext_reorg_roi_54_126/ipsc-->mAP
<a id="g2_0_53___vita_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_53       @ vita/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999/csv gt_csv_name=annotations_0_53.csv save_suffix=full-vita gt_pkl=g2_0_53.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___g2_0_53_vita_ext_reorg_roi_54_126_ipsc_"></a>
##### max_length-2       @ g2_0_53/vita/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_max_length-2/csv gt_csv_name=annotations_0_53.csv save_suffix=full-vita-max_length-2 gt_pkl=g2_0_53.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___vita_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_15       @ vita/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15/csv gt_csv_name=annotations_0_15.csv save_suffix=full-vita-g2_0_15 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___g2_0_15_vita_ext_reorg_roi_54_126_ipsc_"></a>
##### max_length-2       @ g2_0_15/vita/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-max_length-2/csv gt_csv_name=annotations_0_15.csv save_suffix=full-vita-g2_0_15-max_length-2 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="vita_inc___ext_reorg_roi_54_126_ips_c_"></a>
### vita-inc       @ ext_reorg_roi_54_126/ipsc-->mAP
<a id="g2_0_53___vita_inc_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_53       @ vita-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_incremental/csv_incremental gt_csv_name=annotations_0_53.csv save_suffix=full-vita-inc gt_pkl=g2_0_53.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_incremental/csv_incremental gt_csv_name=annotations_0_53.csv save_suffix=full-vita-inc show_vis=0 show_tp=1 save_vis=0 nms_thresh=0.2 n_proc=1 iw=1
<a id="max_length_2___g2_0_53_vita_inc_ext_reorg_roi_54_126_ipsc_"></a>
##### max_length-2       @ g2_0_53/vita-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_max_length-2-incremental/csv_incremental gt_csv_name=annotations_0_53.csv save_suffix=full-vita-inc-max_length-2 gt_pkl=g2_0_53.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___vita_inc_ext_reorg_roi_54_126_ipsc_"></a>
#### g2_0_15       @ vita-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-vita-inc-g2_0_15 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
__iw__
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-vita-inc-g2_0_15 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 n_proc=1 iw=1 nms_thresh=0.2
<a id="max_length_2___g2_0_15_vita_inc_ext_reorg_roi_54_126_ipsc_"></a>
##### max_length-2       @ g2_0_15/vita-inc/ext_reorg_roi_54_126/ipsc-->mAP
python3 mAP.py cfg=ipsc_2_class img_paths=../human/ext_reorg_roi.txt det_paths=log/vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-max_length-2-incremental/csv_incremental gt_csv_name=annotations_0_15.csv save_suffix=full-vita-inc-g2_0_15-max_length-2 gt_pkl=g2_0_15.pkl show_vis=0 show_tp=1 save_vis=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="mj_rock_s_"></a>
# mj_rocks
<a id="swi_db4___mj_rocks_"></a>
## swi-db4       @ mj_rocks-->mAP
python3 mAP.py img_root_dir=/data/mojow_rock/rock_dataset4 img_paths=../human/db4.txt det_paths=log/swi/db3_2_to_17_except_6-large_huge/db4/csv labels_path=predefined_classes_rock.txt save_vis=1 show_vis=0 show_stats=1 show_gt=1 ignore_invalid_class=0 gt_csv_name=annotations.csv save_suffix=swi-db4 img_dir_name=images vid_fmt=H264,2,mkv show_tp=0
