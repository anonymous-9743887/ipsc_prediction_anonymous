
<!-- MarkdownTOC -->

- [xml_to_coco](#xml_to_coco_)
    - [mj_rock       @ xml_to_coco](#mj_rock___xml_to_coc_o_)
        - [db4       @ mj_rock/xml_to_coco](#db4___mj_rock_xml_to_coc_o_)
            - [rockmaps       @ db4/mj_rock/xml_to_coco](#rockmaps___db4_mj_rock_xml_to_coc_o_)
            - [rockmaps_syn       @ db4/mj_rock/xml_to_coco](#rockmaps_syn___db4_mj_rock_xml_to_coc_o_)
        - [db3       @ mj_rock/xml_to_coco](#db3___mj_rock_xml_to_coc_o_)
            - [part12       @ db3/mj_rock/xml_to_coco](#part12___db3_mj_rock_xml_to_coc_o_)
            - [part1       @ db3/mj_rock/xml_to_coco](#part1___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ part1/db3/mj_rock/xml_to_coco](#large_huge___part1_db3_mj_rock_xml_to_coc_o_)
            - [part6       @ db3/mj_rock/xml_to_coco](#part6___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ part6/db3/mj_rock/xml_to_coco](#large_huge___part6_db3_mj_rock_xml_to_coc_o_)
            - [september_5_2020       @ db3/mj_rock/xml_to_coco](#september_5_2020___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ september_5_2020/db3/mj_rock/xml_to_coco](#large_huge___september_5_2020_db3_mj_rock_xml_to_coco_)
            - [db3_2_to_17_except_6       @ db3/mj_rock/xml_to_coco](#db3_2_to_17_except_6___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ db3_2_to_17_except_6/db3/mj_rock/xml_to_coco](#large_huge___db3_2_to_17_except_6_db3_mj_rock_xml_to_coco_)
            - [db3_2_to_17_except_6_no_rocks       @ db3/mj_rock/xml_to_coco](#db3_2_to_17_except_6_no_rocks___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ db3_2_to_17_except_6_no_rocks/db3/mj_rock/xml_to_coco](#large_huge___db3_2_to_17_except_6_no_rocks_db3_mj_rock_xml_to_coc_o_)
            - [db3_2_to_17_except_6_with_syn       @ db3/mj_rock/xml_to_coco](#db3_2_to_17_except_6_with_syn___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ db3_2_to_17_except_6_with_syn/db3/mj_rock/xml_to_coco](#large_huge___db3_2_to_17_except_6_with_syn_db3_mj_rock_xml_to_coc_o_)
            - [part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco](#part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ part5_on_september_5_2020/db3/mj_rock/xml_to_coco](#large_huge___part5_on_september_5_2020_db3_mj_rock_xml_to_coc_o_)
            - [part4_on_part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco](#part4_on_part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ part4_on_part5_on_september_5_2020/db3/mj_rock/xml_to_coco](#large_huge___part4_on_part5_on_september_5_2020_db3_mj_rock_xml_to_coco_)
            - [part14_on_part4_on_part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco](#part14_on_part4_on_part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_)
                - [large_huge       @ part14_on_part4_on_part5_on_september_5_2020/db3/mj_rock/xml_to_coco](#large_huge___part14_on_part4_on_part5_on_september_5_2020_db3_mj_rock_xml_to_coco_)
    - [ipsc_2_class       @ xml_to_coco](#ipsc_2_class___xml_to_coc_o_)
        - [all_frames_roi       @ ipsc_2_class/xml_to_coco](#all_frames_roi___ipsc_2_class_xml_to_coco_)
            - [g2_0_37       @ all_frames_roi/ipsc_2_class/xml_to_coco](#g2_0_37___all_frames_roi_ipsc_2_class_xml_to_coc_o_)
            - [g2_38_53       @ all_frames_roi/ipsc_2_class/xml_to_coco](#g2_38_53___all_frames_roi_ipsc_2_class_xml_to_coc_o_)
            - [g2_seq_1_39_53       @ all_frames_roi/ipsc_2_class/xml_to_coco](#g2_seq_1_39_53___all_frames_roi_ipsc_2_class_xml_to_coc_o_)
            - [g3_54_90       @ all_frames_roi/ipsc_2_class/xml_to_coco](#g3_54_90___all_frames_roi_ipsc_2_class_xml_to_coc_o_)
        - [ext_reorg_roi       @ ipsc_2_class/xml_to_coco](#ext_reorg_roi___ipsc_2_class_xml_to_coco_)
            - [g2_0_37       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_0_37___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_validate       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_validate___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [write_masks       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco](#write_masks___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_mask       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_mask___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
            - [g2_38_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_38_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [write_masks       @ g2_38_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#write_masks___g2_38_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_)
            - [g2_15_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_15_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_validate       @ g2_15_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_validate___g2_15_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_)
            - [g2_16_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_16_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [val-30       @ g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#val_30___g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_)
                - [no-val       @ g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_val___g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_)
                    - [no_mask       @ no-val/g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_mask___no_val_g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
            - [g2_0_15       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_0_15___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_mask       @ g2_0_15/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_mask___g2_0_15_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
            - [g2_54_126       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_54_126___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_mask       @ g2_54_126/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_mask___g2_54_126_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
            - [g2_0_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco](#g2_0_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_)
                - [no_mask       @ g2_0_53/ext_reorg_roi/ipsc_2_class/xml_to_coco](#no_mask___g2_0_53_ext_reorg_roi_ipsc_2_class_xml_to_coco_)
        - [ext_reorg_roi-no_annotations       @ ipsc_2_class/xml_to_coco](#ext_reorg_roi_no_annotations___ipsc_2_class_xml_to_coco_)
            - [reorg_roi       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#reorg_roi___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_)
            - [all_frames_roi       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#all_frames_roi___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_)
                - [all_frames_roi_7777_10249_10111_13349       @ all_frames_roi/ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#all_frames_roi_7777_10249_10111_13349___all_frames_roi_ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coco_)
                - [all_frames_roi_8094_13016_11228_15282       @ all_frames_roi/ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#all_frames_roi_8094_13016_11228_15282___all_frames_roi_ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coco_)
            - [Test_211208       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#test_211208___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_)
            - [nd03       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco](#nd03___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_)
        - [g2_4       @ ipsc_2_class/xml_to_coco](#g2_4___ipsc_2_class_xml_to_coco_)
        - [g4       @ ipsc_2_class/xml_to_coco](#g4___ipsc_2_class_xml_to_coco_)
        - [g3       @ ipsc_2_class/xml_to_coco](#g3___ipsc_2_class_xml_to_coco_)
    - [ipsc_5_class       @ xml_to_coco](#ipsc_5_class___xml_to_coc_o_)
        - [Test_211208       @ ipsc_5_class/xml_to_coco](#test_211208___ipsc_5_class_xml_to_coco_)
        - [k       @ ipsc_5_class/xml_to_coco](#k___ipsc_5_class_xml_to_coco_)
        - [nd03       @ ipsc_5_class/xml_to_coco](#nd03___ipsc_5_class_xml_to_coco_)
        - [g3_4s       @ ipsc_5_class/xml_to_coco](#g3_4s___ipsc_5_class_xml_to_coco_)
            - [50_50       @ g3_4s/ipsc_5_class/xml_to_coco](#50_50___g3_4s_ipsc_5_class_xml_to_coco_)
            - [no_val       @ g3_4s/ipsc_5_class/xml_to_coco](#no_val___g3_4s_ipsc_5_class_xml_to_coco_)
        - [g3       @ ipsc_5_class/xml_to_coco](#g3___ipsc_5_class_xml_to_coco_)
            - [50_50       @ g3/ipsc_5_class/xml_to_coco](#50_50___g3_ipsc_5_class_xml_to_coc_o_)
            - [no_val       @ g3/ipsc_5_class/xml_to_coco](#no_val___g3_ipsc_5_class_xml_to_coc_o_)
        - [g4s       @ ipsc_5_class/xml_to_coco](#g4s___ipsc_5_class_xml_to_coco_)
            - [50_50       @ g4s/ipsc_5_class/xml_to_coco](#50_50___g4s_ipsc_5_class_xml_to_coco_)
            - [no_val       @ g4s/ipsc_5_class/xml_to_coco](#no_val___g4s_ipsc_5_class_xml_to_coco_)
    - [ctc       @ xml_to_coco](#ctc___xml_to_coc_o_)
        - [ctc_all       @ ctc/xml_to_coco](#ctc_all___ctc_xml_to_coc_o_)
        - [ctc_BF_C2DL_HSC       @ ctc/xml_to_coco](#ctc_bf_c2dl_hsc___ctc_xml_to_coc_o_)
        - [ctc_BF_C2DL_MuSC       @ ctc/xml_to_coco](#ctc_bf_c2dl_musc___ctc_xml_to_coc_o_)
        - [ctc_DIC_C2DH_HeLa       @ ctc/xml_to_coco](#ctc_dic_c2dh_hela___ctc_xml_to_coc_o_)
        - [ctc_Fluo_C2DL_Huh7       @ ctc/xml_to_coco](#ctc_fluo_c2dl_huh7___ctc_xml_to_coc_o_)
        - [ctc_Fluo_C2DL_MSC       @ ctc/xml_to_coco](#ctc_fluo_c2dl_msc___ctc_xml_to_coc_o_)
        - [ctc_PhC_C2DH_U373       @ ctc/xml_to_coco](#ctc_phc_c2dh_u373___ctc_xml_to_coc_o_)
        - [ctc_PhC_C2DL_PSC       @ ctc/xml_to_coco](#ctc_phc_c2dl_psc___ctc_xml_to_coc_o_)
        - [ctc_Fluo_N2DH_GOWT1       @ ctc/xml_to_coco](#ctc_fluo_n2dh_gowt1___ctc_xml_to_coc_o_)
        - [ctc_Fluo_N2DH_SIM       @ ctc/xml_to_coco](#ctc_fluo_n2dh_sim___ctc_xml_to_coc_o_)
        - [ctc_Fluo_N2DL_HeLa       @ ctc/xml_to_coco](#ctc_fluo_n2dl_hela___ctc_xml_to_coc_o_)
    - [ctmc_all       @ xml_to_coco](#ctmc_all___xml_to_coc_o_)
- [xml_to_ytvis](#xml_to_ytvi_s_)
    - [mj_rock       @ xml_to_ytvis](#mj_rock___xml_to_ytvis_)
        - [db4       @ mj_rock/xml_to_ytvis](#db4___mj_rock_xml_to_ytvis_)
            - [all       @ db4/mj_rock/xml_to_ytvis](#all___db4_mj_rock_xml_to_ytvis_)
        - [db3-part12       @ mj_rock/xml_to_ytvis](#db3_part12___mj_rock_xml_to_ytvis_)
            - [large_huge       @ db3-part12/mj_rock/xml_to_ytvis](#large_huge___db3_part12_mj_rock_xml_to_ytvi_s_)
        - [db3-part4       @ mj_rock/xml_to_ytvis](#db3_part4___mj_rock_xml_to_ytvis_)
            - [all       @ db3-part4/mj_rock/xml_to_ytvis](#all___db3_part4_mj_rock_xml_to_ytvis_)
            - [large_huge       @ db3-part4/mj_rock/xml_to_ytvis](#large_huge___db3_part4_mj_rock_xml_to_ytvis_)
            - [large_huge_target_ids       @ db3-part4/mj_rock/xml_to_ytvis](#large_huge_target_ids___db3_part4_mj_rock_xml_to_ytvis_)
        - [db3_2_to_17_except_6       @ mj_rock/xml_to_ytvis](#db3_2_to_17_except_6___mj_rock_xml_to_ytvis_)
            - [all       @ db3_2_to_17_except_6/mj_rock/xml_to_ytvis](#all___db3_2_to_17_except_6_mj_rock_xml_to_ytvi_s_)
            - [large_huge       @ db3_2_to_17_except_6/mj_rock/xml_to_ytvis](#large_huge___db3_2_to_17_except_6_mj_rock_xml_to_ytvi_s_)
        - [db3_2_to_17_except_6_with_syn       @ mj_rock/xml_to_ytvis](#db3_2_to_17_except_6_with_syn___mj_rock_xml_to_ytvis_)
            - [large_huge       @ db3_2_to_17_except_6_with_syn/mj_rock/xml_to_ytvis](#large_huge___db3_2_to_17_except_6_with_syn_mj_rock_xml_to_ytvis_)
        - [september_5_2020       @ mj_rock/xml_to_ytvis](#september_5_2020___mj_rock_xml_to_ytvis_)
            - [all       @ september_5_2020/mj_rock/xml_to_ytvis](#all___september_5_2020_mj_rock_xml_to_ytvi_s_)
            - [large_huge       @ september_5_2020/mj_rock/xml_to_ytvis](#large_huge___september_5_2020_mj_rock_xml_to_ytvi_s_)
                - [max_length-200       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis](#max_length_200___large_huge_september_5_2020_mj_rock_xml_to_ytvis_)
                - [max_length-50       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis](#max_length_50___large_huge_september_5_2020_mj_rock_xml_to_ytvis_)
                - [max_length-20       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis](#max_length_20___large_huge_september_5_2020_mj_rock_xml_to_ytvis_)
        - [all_frames_roi_g2_38_53       @ mj_rock/xml_to_ytvis](#all_frames_roi_g2_38_53___mj_rock_xml_to_ytvis_)
        - [all_frames_roi_g2_seq_1_38_53       @ mj_rock/xml_to_ytvis](#all_frames_roi_g2_seq_1_38_53___mj_rock_xml_to_ytvis_)
        - [all_frames_roi_g3_53_92       @ mj_rock/xml_to_ytvis](#all_frames_roi_g3_53_92___mj_rock_xml_to_ytvis_)
    - [ext_reorg_roi_g2_0_37       @ xml_to_ytvis](#ext_reorg_roi_g2_0_37___xml_to_ytvis_)
        - [max_length-20       @ ext_reorg_roi_g2_0_37/xml_to_ytvis](#max_length_20___ext_reorg_roi_g2_0_37_xml_to_ytvis_)
        - [max_length-10       @ ext_reorg_roi_g2_0_37/xml_to_ytvis](#max_length_10___ext_reorg_roi_g2_0_37_xml_to_ytvis_)
    - [ext_reorg_roi_g2_38_53       @ xml_to_ytvis](#ext_reorg_roi_g2_38_53___xml_to_ytvis_)
        - [incremental       @ ext_reorg_roi_g2_38_53/xml_to_ytvis](#incremental___ext_reorg_roi_g2_38_53_xml_to_ytvi_s_)
    - [ext_reorg_roi_g2_16_53       @ xml_to_ytvis](#ext_reorg_roi_g2_16_53___xml_to_ytvis_)
    - [ext_reorg_roi_g2_0_15       @ xml_to_ytvis](#ext_reorg_roi_g2_0_15___xml_to_ytvis_)
        - [incremental       @ ext_reorg_roi_g2_0_15/xml_to_ytvis](#incremental___ext_reorg_roi_g2_0_15_xml_to_ytvis_)
            - [max_length-2       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis](#max_length_2___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_)
            - [max_length-4       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis](#max_length_4___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_)
            - [max_length-10       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis](#max_length_10___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_)
    - [ext_reorg_roi_g2_54_126       @ xml_to_ytvis](#ext_reorg_roi_g2_54_126___xml_to_ytvis_)
        - [subseq       @ ext_reorg_roi_g2_54_126/xml_to_ytvis](#subseq___ext_reorg_roi_g2_54_126_xml_to_ytvis_)
    - [ext_reorg_roi_g2_0_53       @ xml_to_ytvis](#ext_reorg_roi_g2_0_53___xml_to_ytvis_)
        - [incremental       @ ext_reorg_roi_g2_0_53/xml_to_ytvis](#incremental___ext_reorg_roi_g2_0_53_xml_to_ytvis_)
- [coco_to_xml](#coco_to_xml_)
    - [all_frames_roi_g2_0_37       @ coco_to_xml](#all_frames_roi_g2_0_37___coco_to_xm_l_)
        - [swi       @ all_frames_roi_g2_0_37/coco_to_xml](#swi___all_frames_roi_g2_0_37_coco_to_xml_)
        - [idol       @ all_frames_roi_g2_0_37/coco_to_xml](#idol___all_frames_roi_g2_0_37_coco_to_xml_)
        - [seqformer       @ all_frames_roi_g2_0_37/coco_to_xml](#seqformer___all_frames_roi_g2_0_37_coco_to_xml_)
        - [vita-swin       @ all_frames_roi_g2_0_37/coco_to_xml](#vita_swin___all_frames_roi_g2_0_37_coco_to_xml_)
        - [vita-r50       @ all_frames_roi_g2_0_37/coco_to_xml](#vita_r50___all_frames_roi_g2_0_37_coco_to_xml_)
        - [vita-r101       @ all_frames_roi_g2_0_37/coco_to_xml](#vita_r101___all_frames_roi_g2_0_37_coco_to_xml_)
    - [ext_reorg_roi_g2_0_37       @ coco_to_xml](#ext_reorg_roi_g2_0_37___coco_to_xm_l_)
        - [swi       @ ext_reorg_roi_g2_0_37/coco_to_xml](#swi___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [nms       @ swi/ext_reorg_roi_g2_0_37/coco_to_xml](#nms___swi_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [swi-no_validate-rcnn       @ ext_reorg_roi_g2_0_37/coco_to_xml](#swi_no_validate_rcnn___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [swi-no_validate-rcnn-win7       @ ext_reorg_roi_g2_0_37/coco_to_xml](#swi_no_validate_rcnn_win7___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [swi-rcnn-win7       @ ext_reorg_roi_g2_0_37/coco_to_xml](#swi_rcnn_win7___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [cvnxt-base       @ ext_reorg_roi_g2_0_37/coco_to_xml](#cvnxt_base___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [nms       @ cvnxt-base/ext_reorg_roi_g2_0_37/coco_to_xml](#nms___cvnxt_base_ext_reorg_roi_g2_0_37_coco_to_xml_)
        - [cvnxt-large       @ ext_reorg_roi_g2_0_37/coco_to_xml](#cvnxt_large___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [nms       @ cvnxt-large/ext_reorg_roi_g2_0_37/coco_to_xml](#nms___cvnxt_large_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [idol       @ ext_reorg_roi_g2_0_37/coco_to_xml](#idol___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [idol-incremental       @ ext_reorg_roi_g2_0_37/coco_to_xml](#idol_incremental___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [probs       @ idol-incremental/ext_reorg_roi_g2_0_37/coco_to_xml](#probs___idol_incremental_ext_reorg_roi_g2_0_37_coco_to_xml_)
        - [seqformer       @ ext_reorg_roi_g2_0_37/coco_to_xml](#seqformer___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [seqformer-incremental       @ ext_reorg_roi_g2_0_37/coco_to_xml](#seqformer_incremental___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [nms       @ seqformer-incremental/ext_reorg_roi_g2_0_37/coco_to_xml](#nms___seqformer_incremental_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [probs       @ seqformer-incremental/ext_reorg_roi_g2_0_37/coco_to_xml](#probs___seqformer_incremental_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [vita-swin       @ ext_reorg_roi_g2_0_37/coco_to_xml](#vita_swin___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
            - [incremental       @ vita-swin/ext_reorg_roi_g2_0_37/coco_to_xml](#incremental___vita_swin_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
                - [nms       @ incremental/vita-swin/ext_reorg_roi_g2_0_37/coco_to_xml](#nms___incremental_vita_swin_ext_reorg_roi_g2_0_37_coco_to_xm_l_)
        - [vita-r50       @ ext_reorg_roi_g2_0_37/coco_to_xml](#vita_r50___ext_reorg_roi_g2_0_37_coco_to_xm_l_)
    - [ext_reorg_roi_g2_16_53       @ coco_to_xml](#ext_reorg_roi_g2_16_53___coco_to_xm_l_)
        - [yl8       @ ext_reorg_roi_g2_16_53/coco_to_xml](#yl8___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [val       @ yl8/ext_reorg_roi_g2_16_53/coco_to_xml](#val___yl8_ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [seq-val       @ yl8/ext_reorg_roi_g2_16_53/coco_to_xml](#seq_val___yl8_ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [swi       @ ext_reorg_roi_g2_16_53/coco_to_xml](#swi___ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [swi-rcnn       @ ext_reorg_roi_g2_16_53/coco_to_xml](#swi_rcnn___ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [cvnxt       @ ext_reorg_roi_g2_16_53/coco_to_xml](#cvnxt___ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [idol       @ ext_reorg_roi_g2_16_53/coco_to_xml](#idol___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [probs       @ idol/ext_reorg_roi_g2_16_53/coco_to_xml](#probs___idol_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
        - [idol-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml](#idol_inc___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [nms       @ idol-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#nms___idol_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
        - [idol-inc-probs       @ ext_reorg_roi_g2_16_53/coco_to_xml](#idol_inc_probs___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [nms-01       @ idol-inc-probs/ext_reorg_roi_g2_16_53/coco_to_xml](#nms_01___idol_inc_probs_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
        - [seqformer       @ ext_reorg_roi_g2_16_53/coco_to_xml](#seqformer___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [probs       @ seqformer/ext_reorg_roi_g2_16_53/coco_to_xml](#probs___seqformer_ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [seqformer-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml](#seqformer_inc___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [nms       @ seqformer-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#nms___seqformer_inc_ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [probs       @ seqformer-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#probs___seqformer_inc_ext_reorg_roi_g2_16_53_coco_to_xml_)
        - [vita       @ ext_reorg_roi_g2_16_53/coco_to_xml](#vita___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [0119999       @ vita/ext_reorg_roi_g2_16_53/coco_to_xml](#0119999___vita_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
            - [0329999       @ vita/ext_reorg_roi_g2_16_53/coco_to_xml](#0329999___vita_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
        - [vita-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml](#vita_inc___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [0119999       @ vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#0119999___vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
            - [0329999       @ vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#0329999___vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
                - [nms       @ 0329999/vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml](#nms___0329999_vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
        - [vita-inc-retrain       @ ext_reorg_roi_g2_16_53/coco_to_xml](#vita_inc_retrain___ext_reorg_roi_g2_16_53_coco_to_xml_)
            - [0004999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml](#0004999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
            - [0079999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml](#0079999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
            - [0104999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml](#0104999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_)
    - [ext_reorg_roi_g2_54_126       @ coco_to_xml](#ext_reorg_roi_g2_54_126___coco_to_xm_l_)
        - [yl8       @ ext_reorg_roi_g2_54_126/coco_to_xml](#yl8___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
        - [swi       @ ext_reorg_roi_g2_54_126/coco_to_xml](#swi___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_15       @ swi/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___swi_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
        - [cvnxt-large       @ ext_reorg_roi_g2_54_126/coco_to_xml](#cvnxt_large___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_15       @ cvnxt-large/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___cvnxt_large_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
        - [cvnxt-base       @ ext_reorg_roi_g2_54_126/coco_to_xml](#cvnxt_base___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_15       @ cvnxt-base/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___cvnxt_base_ext_reorg_roi_g2_54_126_coco_to_xml_)
        - [idol-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml](#idol_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_53       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_53___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
            - [max_length-2       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
            - [g2_0_15       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
            - [max_length-2       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml__1)
        - [seqformer-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml](#seqformer_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_53       @ seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_53___seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
                - [max_length-2       @ g2_0_53/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_53_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
                - [max_length-10       @ g2_0_53/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_10___g2_0_53_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_15       @ seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
                - [max_length-2       @ g2_0_15/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_15_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_)
        - [vita       @ ext_reorg_roi_g2_54_126/coco_to_xml](#vita___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_53       @ vita/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_53___vita_ext_reorg_roi_g2_54_126_coco_to_xml_)
                - [max_length-2       @ g2_0_53/vita/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_53_vita_ext_reorg_roi_g2_54_126_coco_to_xml_)
            - [g2_0_15       @ vita/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___vita_ext_reorg_roi_g2_54_126_coco_to_xml_)
                - [max_length-2       @ g2_0_15/vita/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_15_vita_ext_reorg_roi_g2_54_126_coco_to_xml_)
        - [vita-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml](#vita_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_)
            - [g2_0_53       @ vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_53___vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
                - [max_length-2       @ g2_0_53/vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_53_vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
            - [g2_0_15       @ vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#g2_0_15___vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
                - [max_length-2       @ g2_0_15/vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml](#max_length_2___g2_0_15_vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_)
    - [db3_2_to_17_except_6       @ coco_to_xml](#db3_2_to_17_except_6___coco_to_xm_l_)
        - [idol       @ db3_2_to_17_except_6/coco_to_xml](#idol___db3_2_to_17_except_6_coco_to_xml_)
        - [vita       @ db3_2_to_17_except_6/coco_to_xml](#vita___db3_2_to_17_except_6_coco_to_xml_)
            - [r50       @ vita/db3_2_to_17_except_6/coco_to_xml](#r50___vita_db3_2_to_17_except_6_coco_to_xm_l_)
            - [r101       @ vita/db3_2_to_17_except_6/coco_to_xml](#r101___vita_db3_2_to_17_except_6_coco_to_xm_l_)

<!-- /MarkdownTOC -->

<a id="xml_to_coco_"></a>
# xml_to_coco

<a id="mj_rock___xml_to_coc_o_"></a>
## mj_rock       @ xml_to_coco-->coco

<a id="db4___mj_rock_xml_to_coc_o_"></a>
### db4       @ mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset4 seq_paths=db4.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db4.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="rockmaps___db4_mj_rock_xml_to_coc_o_"></a>
#### rockmaps       @ db4/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset4/rockmaps seq_paths=db4.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db4-rockmaps.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="rockmaps_syn___db4_mj_rock_xml_to_coc_o_"></a>
#### rockmaps_syn       @ db4/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset4/rockmaps/syn seq_paths=db4_syn.txt class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=/data/mojow_rock/rock_dataset4/db4-rockmaps_syn.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="db3___mj_rock_xml_to_coc_o_"></a>
### db3       @ mj_rock/xml_to_coco-->coco
<a id="part12___db3_mj_rock_xml_to_coc_o_"></a>
#### part12       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part12 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_part12-large_huge.json val_ratio=0.3 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0

<a id="part1___db3_mj_rock_xml_to_coc_o_"></a>
#### part1       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part1 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=part1.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___part1_db3_mj_rock_xml_to_coc_o_"></a>
##### large_huge       @ part1/db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part1 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=part1-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="part6___db3_mj_rock_xml_to_coc_o_"></a>
#### part6       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part1 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=part6.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___part6_db3_mj_rock_xml_to_coc_o_"></a>
##### large_huge       @ part6/db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part6 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=part6-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="september_5_2020___db3_mj_rock_xml_to_coc_o_"></a>
#### september_5_2020       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=september_5_2020.json val_ratio=0 min_val=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___september_5_2020_db3_mj_rock_xml_to_coco_"></a>
##### large_huge       @ september_5_2020/db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=september_5_2020-large_huge.json val_ratio=0 min_val=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

__no_annotations__
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=september_5_2020-large_huge.json val_ratio=0 min_val=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0 no_annotations=1

<a id="db3_2_to_17_except_6___db3_mj_rock_xml_to_coc_o_"></a>
#### db3_2_to_17_except_6       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_2_to_17_except_6.json val_ratio=0.3 allow_missing_images=1 remove_mj_dir_suffix=0 get_img_stats=0

python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_2_to_17_except_6.json val_ratio=0 allow_missing_images=1 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___db3_2_to_17_except_6_db3_mj_rock_xml_to_coco_"></a>
##### large_huge       @ db3_2_to_17_except_6/db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_2_to_17_except_6-large_huge.json val_ratio=0.3 dir_suffix=large_huge allow_missing_images=1 remove_mj_dir_suffix=0 get_img_stats=0

<a id="db3_2_to_17_except_6_no_rocks___db3_mj_rock_xml_to_coc_o_"></a>
#### db3_2_to_17_except_6_no_rocks       @ db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6_no_rocks.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_2_to_17_except_6_no_rocks.json val_ratio=0 allow_missing_images=1 remove_mj_dir_suffix=0 get_img_stats=1
pix_vals_mean: [143.90739512604202, 137.85737889429524, 138.77791972367567]
pix_vals_std: [39.216714984858854, 43.18105474265608, 43.806309282665055]


<a id="large_huge___db3_2_to_17_except_6_no_rocks_db3_mj_rock_xml_to_coc_o_"></a>
##### large_huge       @ db3_2_to_17_except_6_no_rocks/db3/mj_rock/xml_to_coco-->coco
python3 xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6_no_rocks.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt output_json=db3_2_to_17_except_6_no_rocks-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=1 remove_mj_dir_suffix=0 get_img_stats=1
pix_vals_mean: [143.90739512604202, 137.85737889429524, 138.77791972367567]
pix_vals_std: [39.216714984858854, 43.18105474265608, 43.806309282665055]

<a id="db3_2_to_17_except_6_with_syn___db3_mj_rock_xml_to_coc_o_"></a>
#### db3_2_to_17_except_6_with_syn       @ db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6_with_syn.txt class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=db3_2_to_17_except_6_with_syn.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___db3_2_to_17_except_6_with_syn_db3_mj_rock_xml_to_coc_o_"></a>
##### large_huge       @ db3_2_to_17_except_6_with_syn/db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6_with_syn.txt class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=db3_2_to_17_except_6_with_syn-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_"></a>
#### part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part5_on_september_5_2020.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___part5_on_september_5_2020_db3_mj_rock_xml_to_coc_o_"></a>
##### large_huge       @ part5_on_september_5_2020/db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part5_on_september_5_2020-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="part4_on_part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_"></a>
#### part4_on_part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part4_on_part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part4_on_part5_on_september_5_2020.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___part4_on_part5_on_september_5_2020_db3_mj_rock_xml_to_coco_"></a>
##### large_huge       @ part4_on_part5_on_september_5_2020/db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part4_on_part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part4_on_part5_on_september_5_2020-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="part14_on_part4_on_part5_on_september_5_2020___db3_mj_rock_xml_to_coc_o_"></a>
#### part14_on_part4_on_part5_on_september_5_2020       @ db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part14_on_part4_on_part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part14_on_part4_on_part5_on_september_5_2020.json val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="large_huge___part14_on_part4_on_part5_on_september_5_2020_db3_mj_rock_xml_to_coco_"></a>
##### large_huge       @ part14_on_part4_on_part5_on_september_5_2020/db3/mj_rock/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=syn/part14_on_part4_on_part5_on_september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock_syn.txt output_json=part14_on_part4_on_part5_on_september_5_2020-large_huge.json val_ratio=0 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=0

<a id="ipsc_2_class___xml_to_coc_o_"></a>
## ipsc_2_class       @ xml_to_coco-->coco
<a id="all_frames_roi___ipsc_2_class_xml_to_coco_"></a>
### all_frames_roi       @ ipsc_2_class/xml_to_coco-->coco
<a id="g2_0_37___all_frames_roi_ipsc_2_class_xml_to_coc_o_"></a>
#### g2_0_37       @ all_frames_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_g2_0_37.json start_frame_id=0 end_frame_id=38 ignore_invalid_label=1 val_ratio=0.2

<a id="g2_38_53___all_frames_roi_ipsc_2_class_xml_to_coc_o_"></a>
#### g2_38_53       @ all_frames_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_g2_38_53.json start_frame_id=39 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0

<a id="g2_seq_1_39_53___all_frames_roi_ipsc_2_class_xml_to_coc_o_"></a>
#### g2_seq_1_39_53       @ all_frames_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_g2_seq_1_39_53.json start_frame_id=39 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 n_seq=1

<a id="g3_54_90___all_frames_roi_ipsc_2_class_xml_to_coc_o_"></a>
#### g3_54_90       @ all_frames_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_g3_54_90.json start_frame_id=54 end_frame_id=92 ignore_invalid_label=1 val_ratio=0.2

<a id="ext_reorg_roi___ipsc_2_class_xml_to_coco_"></a>
### ext_reorg_roi       @ ipsc_2_class/xml_to_coco-->coco
<a id="g2_0_37___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_0_37       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_37.json start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0.2

<a id="no_validate___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### no_validate       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_37.json start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0

__only_list__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_37.json start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 only_list=1

```
1209 / 1209 valid images :: 7551 objects  ipsc: 1874 diff: 5677
pix_vals_mean: [130.26014205414378, 130.26014205414378, 130.26014205414378]
pix_vals_std: [16.855180446630406, 16.855180446630406, 16.855180446630406]
saving output json for 1209 images to: /data/ipsc/well3/all_frames_roi/ext_reorg_roi_g2_0_37.json
```

<a id="write_masks___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### write_masks       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_37.json start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 write_masks=1 get_img_stats=0

<a id="no_mask___g2_0_37_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### no_mask       @ g2_0_37/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_37-no_mask.json start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 enable_mask=0
```
1209 / 1209 valid images :: 7557 objects  ipsc: 1877 diff: 5680
pix_vals_mean: [130.2047103166563, 130.2047103166563, 130.2047103166563]
pix_vals_std: [16.979544725358632, 16.979544725358632, 16.979544725358632]
```
<a id="g2_38_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_38_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_38_53.json start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0
```
pix_vals_mean: [122.33588318869438, 122.33588318869438, 122.33588318869438]
pix_vals_std: [21.941942680167365, 21.941942680167365, 21.941942680167365]
```
__only_list__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_38_53.json start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 only_list=1

<a id="write_masks___g2_38_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_"></a>
##### write_masks       @ g2_38_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_38_53.json start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 write_masks=1 get_img_stats=0

<a id="g2_15_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_15_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_15_53.json start_frame_id=15 end_frame_id=53 ignore_invalid_label=1 val_ratio=0.2
```
pix_vals_mean: [126.62072260746325, 126.62072260746325, 126.62072260746325]
pix_vals_std: [19.203380328648525, 19.203380328648525, 19.203380328648525]
```
<a id="no_validate___g2_15_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_"></a>
##### no_validate       @ g2_15_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_15_53.json start_frame_id=15 end_frame_id=53 ignore_invalid_label=1 val_ratio=0

<a id="g2_16_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_16_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
<a id="val_30___g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_"></a>
##### val-30       @ g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
__only_list__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_16_53.json start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=0.3 only_list=1 shuffle=1
__only_list-seq__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_16_53-seq.json start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=-0.3 only_list=1 shuffle=0

<a id="no_val___g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coc_o_"></a>
##### no-val       @ g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_16_53.json start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=0

```
pix_vals_mean: [126.21, 126.21, 126.21]
pix_vals_std: [19.33, 19.33, 19.33]
```
__only_list__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_16_53.json start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 only_list=1

<a id="no_mask___no_val_g2_16_53_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
###### no_mask       @ no-val/g2_16_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_16_53-no_mask.json start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 enable_mask=0

<a id="g2_0_15___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_0_15       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_15.json start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 get_img_stats=0
__only_list__
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_15.json start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 get_img_stats=0 only_list=1

<a id="no_mask___g2_0_15_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### no_mask       @ g2_0_15/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_15-no_mask.json start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 get_img_stats=0 enable_mask=0

<a id="g2_54_126___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_54_126       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_54_126.json start_frame_id=54 end_frame_id=126 ignore_invalid_label=1 val_ratio=0 get_img_stats=1
```
pix_vals_mean: [118.06, 118.06, 118.06]
pix_vals_std: [23.99, 23.99, 23.99]
```
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_54_126.json start_frame_id=54 end_frame_id=126 ignore_invalid_label=1 val_ratio=0 get_img_stats=1 only_list=1

<a id="no_mask___g2_54_126_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### no_mask       @ g2_54_126/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_54_126-no_mask.json start_frame_id=54 end_frame_id=126 ignore_invalid_label=1 val_ratio=0 get_img_stats=0 enable_mask=0

<a id="g2_0_53___ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
#### g2_0_53       @ ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_53.json start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 get_img_stats=1
```
pix_vals_mean: [127.94684054255906, 127.94684054255906, 127.94684054255906]
pix_vals_std: [18.35440641227878, 18.35440641227878, 18.35440641227878]
```
python xml_to_coco.py root_dir=/data/ipsc/well3/images seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_53.json start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 get_img_stats=1 only_list=1

<a id="no_mask___g2_0_53_ext_reorg_roi_ipsc_2_class_xml_to_coco_"></a>
##### no_mask       @ g2_0_53/ext_reorg_roi/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ext_reorg_roi_g2_0_53-no_mask.json start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 get_img_stats=0 enable_mask=0

<a id="ext_reorg_roi_no_annotations___ipsc_2_class_xml_to_coco_"></a>
### ext_reorg_roi-no_annotations       @ ipsc_2_class/xml_to_coco-->coco
<a id="reorg_roi___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_"></a>
#### reorg_roi       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/reorg_roi seq_paths=reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=reorg_roi.json end_frame_id=126 no_annotations=1

<a id="all_frames_roi___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_"></a>
#### all_frames_roi       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi_raw.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi.json no_annotations=1

<a id="all_frames_roi_7777_10249_10111_13349___all_frames_roi_ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coco_"></a>
##### all_frames_roi_7777_10249_10111_13349       @ all_frames_roi/ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/well3/all_frames_roi/all_frames_roi_7777_10249_10111_13349 class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_7777_10249_10111_13349.json no_annotations=1

<a id="all_frames_roi_8094_13016_11228_15282___all_frames_roi_ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coco_"></a>
##### all_frames_roi_8094_13016_11228_15282       @ all_frames_roi/ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/well3/all_frames_roi/all_frames_roi_8094_13016_11228_15282 class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=all_frames_roi_8094_13016_11228_15282.json no_annotations=1

<a id="test_211208___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_"></a>
#### Test_211208       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/images/Test_211208 class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=Test_211208_2_class.json no_annotations=1

<a id="nd03___ext_reorg_roi_no_annotations_ipsc_2_class_xml_to_coc_o_"></a>
#### nd03       @ ext_reorg_roi-no_annotations/ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/images/nd03 class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=nd03_2_class.json no_annotations=1

<a id="g2_4___ipsc_2_class_xml_to_coco_"></a>
### g2_4       @ ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_2_class_raw seq_paths=ipsc_g2_4.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ipsc_2_class_g2_4.json 

<a id="g4___ipsc_2_class_xml_to_coco_"></a>
### g4       @ ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_2_class_raw seq_paths=ipsc_g4.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ipsc_2_class_g4.json 

<a id="g3___ipsc_2_class_xml_to_coco_"></a>
### g3       @ ipsc_2_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_2_class_raw seq_paths=ipsc_g3.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt output_json=ipsc_2_class_g3.json 

<a id="ipsc_5_class___xml_to_coc_o_"></a>
## ipsc_5_class       @ xml_to_coco-->coco

<a id="test_211208___ipsc_5_class_xml_to_coco_"></a>
### Test_211208       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/images/Test_211208 class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=Test_211208.json no_annotations=1

<a id="k___ipsc_5_class_xml_to_coco_"></a>
### k       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=data/k class_names_path=../labelling_tool/data/predefined_classes_person.txt output_json=k.json no_annotations=1

<a id="nd03___ipsc_5_class_xml_to_coco_"></a>
### nd03       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py seq_paths=/data/ipsc/images/nd03 class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=nd03.json no_annotations=1

<a id="g3_4s___ipsc_5_class_xml_to_coco_"></a>
### g3_4s       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class.json 

<a id="50_50___g3_4s_ipsc_5_class_xml_to_coco_"></a>
#### 50_50       @ g3_4s/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_50_50.json val_ratio=0.5 min_val=1

<a id="no_val___g3_4s_ipsc_5_class_xml_to_coco_"></a>
#### no_val       @ g3_4s/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class.json val_ratio=0 min_val=0

<a id="g3___ipsc_5_class_xml_to_coco_"></a>
### g3       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g3.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g3.json

<a id="50_50___g3_ipsc_5_class_xml_to_coc_o_"></a>
#### 50_50       @ g3/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g3.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g3_50_50.json val_ratio=0.5 min_val=1

<a id="no_val___g3_ipsc_5_class_xml_to_coc_o_"></a>
#### no_val       @ g3/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g3.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g3.json val_ratio=0 min_val=0

<a id="g4s___ipsc_5_class_xml_to_coco_"></a>
### g4s       @ ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g4s.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g4s.json

<a id="50_50___g4s_ipsc_5_class_xml_to_coco_"></a>
#### 50_50       @ g4s/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g4s.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g4s_50_50.json val_ratio=0.5 min_val=0

<a id="no_val___g4s_ipsc_5_class_xml_to_coco_"></a>
#### no_val       @ g4s/ipsc_5_class/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/ipsc_5_class_raw seq_paths=ipsc_g4s.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_5_class.txt output_json=ipsc_5_class_g4s.json val_ratio=0 min_val=0


<a id="ctc___xml_to_coc_o_"></a>
## ctc       @ xml_to_coco-->coco

<a id="ctc_all___ctc_xml_to_coc_o_"></a>
### ctc_all       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_all.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_all.json excluded_images_list=missing_seg_images.txt val_ratio=0.3


<a id="ctc_bf_c2dl_hsc___ctc_xml_to_coc_o_"></a>
### ctc_BF_C2DL_HSC       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_BF_C2DL_HSC.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_BF_C2DL_HSC.json excluded_images_list=missing_seg_images.txt val_ratio=0.3

<a id="ctc_bf_c2dl_musc___ctc_xml_to_coc_o_"></a>
### ctc_BF_C2DL_MuSC       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_BF_C2DL_MuSC.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_BF_C2DL_MuSC.json excluded_images_list=missing_seg_images.txt val_ratio=0.3
pix_vals_mean: [108.65, 108.65, 108.65]
pix_vals_std: [13.27, 13.27, 13.27]

<a id="ctc_dic_c2dh_hela___ctc_xml_to_coc_o_"></a>
### ctc_DIC_C2DH_HeLa       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_DIC_C2DH_HeLa.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_DIC_C2DH_HeLa.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [99.09, 99.09, 99.09]
pix_vals_std: [12.34, 12.34, 12.34]

<a id="ctc_fluo_c2dl_huh7___ctc_xml_to_coc_o_"></a>
### ctc_Fluo_C2DL_Huh7       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_Fluo_C2DL_Huh7.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_Fluo_C2DL_Huh7.json excluded_images_list=missing_seg_images.txt val_ratio=0.1

<a id="ctc_fluo_c2dl_msc___ctc_xml_to_coc_o_"></a>
### ctc_Fluo_C2DL_MSC       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_Fluo_C2DL_MSC.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_Fluo_C2DL_MSC.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [25.06, 25.06, 25.06]
pix_vals_std: [13.85, 13.85, 13.85]

<a id="ctc_phc_c2dh_u373___ctc_xml_to_coc_o_"></a>
### ctc_PhC_C2DH_U373       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_PhC_C2DH_U373.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_PhC_C2DH_U373.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [87.98, 87.98, 87.98]
pix_vals_std: [13.71, 13.71, 13.71]

<a id="ctc_phc_c2dl_psc___ctc_xml_to_coc_o_"></a>
### ctc_PhC_C2DL_PSC       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_PhC_C2DL_PSC.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_PhC_C2DL_PSC.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [135.42, 135.42, 135.42]
pix_vals_std: [24.22, 24.22, 24.22]

<a id="ctc_fluo_n2dh_gowt1___ctc_xml_to_coc_o_"></a>
### ctc_Fluo_N2DH_GOWT1       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_Fluo_N2DH_GOWT1.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_Fluo_N2DH_GOWT1.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [4.61, 4.61, 4.61]
pix_vals_std: [14.15, 14.15, 14.15]

<a id="ctc_fluo_n2dh_sim___ctc_xml_to_coc_o_"></a>
### ctc_Fluo_N2DH_SIM       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_Fluo_N2DH_SIM.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_Fluo_N2DH_SIM.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [21.40, 21.40, 21.40]
pix_vals_std: [9.70, 9.70, 9.70]

<a id="ctc_fluo_n2dl_hela___ctc_xml_to_coc_o_"></a>
### ctc_Fluo_N2DL_HeLa       @ ctc/xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTC/Images seq_paths=ctc_Fluo_N2DL_HeLa.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctc_Fluo_N2DL_HeLa.json excluded_images_list=missing_seg_images.txt val_ratio=0.1
pix_vals_mean: [9.75, 9.75, 9.75]
pix_vals_std: [15.87, 15.87, 15.87]

<a id="ctmc_all___xml_to_coc_o_"></a>
## ctmc_all       @ xml_to_coco-->coco
python xml_to_coco.py root_dir=/data/CTMC/Images seq_paths=ctmc_train.txt class_names_path=../labelling_tool/data/predefined_classes_cell.txt output_json=ctmc_train.json val_ratio=0.3 enable_mask=0

<a id="xml_to_ytvi_s_"></a>
# xml_to_ytvis

<a id="mj_rock___xml_to_ytvis_"></a>
## mj_rock       @ xml_to_ytvis-->coco

<a id="db4___mj_rock_xml_to_ytvis_"></a>
### db4       @ mj_rock/xml_to_ytvis-->coco
<a id="all___db4_mj_rock_xml_to_ytvis_"></a>
#### all       @ db4/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset4 seq_paths=db4.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=0 get_img_stats=1 description=mj_rock-db4 save_masks=0 subseq=1 infer_target_id=1 n_proc=1

pix_vals_mean: [128.24416458682276, 128.80643404991795, 129.93059506678998]
pix_vals_std: [24.073809895323944, 25.343111484178248, 25.39594219533212]


<a id="db3_part12___mj_rock_xml_to_ytvis_"></a>
### db3-part12       @ mj_rock/xml_to_ytvis-->coco
<a id="large_huge___db3_part12_mj_rock_xml_to_ytvi_s_"></a>
#### large_huge       @ db3-part12/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part12 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0.3 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3-part12-large_huge save_masks=1

<a id="db3_part4___mj_rock_xml_to_ytvis_"></a>
### db3-part4       @ mj_rock/xml_to_ytvis-->coco
<a id="all___db3_part4_mj_rock_xml_to_ytvis_"></a>
#### all       @ db3-part4/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part4 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6 save_masks=0 subseq=1 infer_target_id=1 n_proc=1

<a id="large_huge___db3_part4_mj_rock_xml_to_ytvis_"></a>
#### large_huge       @ db3-part4/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part4 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6-large_huge save_masks=0 subseq=1 infer_target_id=1 n_proc=6 dir_suffix=large_huge

<a id="large_huge_target_ids___db3_part4_mj_rock_xml_to_ytvis_"></a>
#### large_huge_target_ids       @ db3-part4/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=part4 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6-large_huge save_masks=0 subseq=1 infer_target_id=0 n_proc=6 dir_suffix=large_huge_target_ids

<a id="db3_2_to_17_except_6___mj_rock_xml_to_ytvis_"></a>
### db3_2_to_17_except_6       @ mj_rock/xml_to_ytvis-->coco
<a id="all___db3_2_to_17_except_6_mj_rock_xml_to_ytvi_s_"></a>
#### all       @ db3_2_to_17_except_6/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6 save_masks=0 subseq=1 infer_target_id=1 n_proc=6

<a id="large_huge___db3_2_to_17_except_6_mj_rock_xml_to_ytvi_s_"></a>
#### large_huge       @ db3_2_to_17_except_6/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6-large_huge save_masks=0 subseq=1 infer_target_id=1 dir_suffix=large_huge n_proc=24

<a id="db3_2_to_17_except_6_with_syn___mj_rock_xml_to_ytvis_"></a>
### db3_2_to_17_except_6_with_syn       @ mj_rock/xml_to_ytvis-->coco
<a id="large_huge___db3_2_to_17_except_6_with_syn_mj_rock_xml_to_ytvis_"></a>
#### large_huge       @ db3_2_to_17_except_6_with_syn/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=db3_2_to_17_except_6_with_syn.txt class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0.3 dir_suffix=large_huge allow_missing_images=0 remove_mj_dir_suffix=1 get_img_stats=0 description=mj_rock-db3_2_to_17_except_6_with_syn-large_huge save_masks=1

<a id="september_5_2020___mj_rock_xml_to_ytvis_"></a>
### september_5_2020       @ mj_rock/xml_to_ytvis-->coco

<a id="all___september_5_2020_mj_rock_xml_to_ytvi_s_"></a>
#### all       @ september_5_2020/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 get_img_stats=0 description=mj_rock-september_5_2020 save_masks=1 subseq=1 infer_target_id=1 min_length=1 n_proc=12 max_length=200

<a id="large_huge___september_5_2020_mj_rock_xml_to_ytvi_s_"></a>
#### large_huge       @ september_5_2020/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 get_img_stats=0 description=mj_rock-september_5_2020-large_huge save_masks=0 subseq=1 infer_target_id=1 dir_suffix=large_huge min_length=1 n_proc=12

<a id="max_length_200___large_huge_september_5_2020_mj_rock_xml_to_ytvis_"></a>
##### max_length-200       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 get_img_stats=0 description=mj_rock-september_5_2020 save_masks=0 subseq=1 infer_target_id=1 dir_suffix=large_huge min_length=1 n_proc=12 max_length=200

<a id="max_length_50___large_huge_september_5_2020_mj_rock_xml_to_ytvis_"></a>
##### max_length-50       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 get_img_stats=0 description=mj_rock-september_5_2020 save_masks=0 subseq=1 infer_target_id=1 dir_suffix=large_huge min_length=1 n_proc=12 max_length=50

<a id="max_length_20___large_huge_september_5_2020_mj_rock_xml_to_ytvis_"></a>
##### max_length-20       @ large_huge/september_5_2020/mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/mojow_rock/rock_dataset3 seq_paths=september_5_2020 class_names_path=../labelling_tool/data/predefined_classes_rock.txt val_ratio=0 allow_missing_images=0 get_img_stats=0 description=mj_rock-september_5_2020 save_masks=0 subseq=1 infer_target_id=1 dir_suffix=large_huge min_length=1 n_proc=12 max_length=20


<a id="all_frames_roi_g2_38_53___mj_rock_xml_to_ytvis_"></a>
### all_frames_roi_g2_38_53       @ mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 allow_missing_images=0 get_img_stats=0 description=ipsc-all_frames_roi_g2_38_53 save_masks=0 coco_rle=1

<a id="all_frames_roi_g2_seq_1_38_53___mj_rock_xml_to_ytvis_"></a>
### all_frames_roi_g2_seq_1_38_53       @ mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt n_seq=1 class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 allow_missing_images=0 get_img_stats=0 description=ipsc-all_frames_roi_g2_seq_1_38_53 save_masks=0 coco_rle=1

<a id="all_frames_roi_g3_53_92___mj_rock_xml_to_ytvis_"></a>
### all_frames_roi_g3_53_92       @ mj_rock/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=all_frames_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=53 end_frame_id=92 ignore_invalid_label=1 val_ratio=0 min_val=0 allow_missing_images=0 get_img_stats=1 description=ipsc-all_frames_roi_g3_53_92 save_masks=1


<a id="ext_reorg_roi_g2_0_37___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_0_37       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_37 save_masks=0

<a id="max_length_20___ext_reorg_roi_g2_0_37_xml_to_ytvis_"></a>
### max_length-20       @ ext_reorg_roi_g2_0_37/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_37 save_masks=0 max_length=20 n_proc=12

<a id="max_length_10___ext_reorg_roi_g2_0_37_xml_to_ytvis_"></a>
### max_length-10       @ ext_reorg_roi_g2_0_37/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=37 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_37 save_masks=0 max_length=10 n_proc=12

<a id="ext_reorg_roi_g2_38_53___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_38_53       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_38_53 save_masks=0 n_proc=12

<a id="incremental___ext_reorg_roi_g2_38_53_xml_to_ytvi_s_"></a>
### incremental       @ ext_reorg_roi_g2_38_53/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=38 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 min_val=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_38_53 save_masks=0 n_proc=24 incremental=1

<a id="ext_reorg_roi_g2_16_53___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_16_53       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=16 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_16_53 save_masks=0 subseq=1 subseq_split_ids=21 n_proc=12

<a id="ext_reorg_roi_g2_0_15___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_0_15       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=12
__max_length-2__
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=12 max_length=2

<a id="incremental___ext_reorg_roi_g2_0_15_xml_to_ytvis_"></a>
### incremental       @ ext_reorg_roi_g2_0_15/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=24 incremental=1
<a id="max_length_2___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_"></a>
#### max_length-2       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=2 incremental=1 max_length=2
<a id="max_length_4___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_"></a>
#### max_length-4       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=2 incremental=1 max_length=4
<a id="max_length_10___incremental_ext_reorg_roi_g2_0_15_xml_to_ytvis_"></a>
#### max_length-10       @ incremental/ext_reorg_roi_g2_0_15/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=15 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_15 save_masks=0 n_proc=2 incremental=1 max_length=10

<a id="ext_reorg_roi_g2_54_126___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_54_126       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=54 end_frame_id=126 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_54_126 save_masks=0 n_proc=12
```
pix_vals_mean: [118.06, 118.06, 118.06]
pix_vals_std: [23.99, 23.99, 23.99]
```
<a id="subseq___ext_reorg_roi_g2_54_126_xml_to_ytvis_"></a>
### subseq       @ ext_reorg_roi_g2_54_126/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=54 end_frame_id=126 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_54_126 save_masks=0 n_proc=12 subseq=1 subseq_split_ids=15 n_proc=12

<a id="ext_reorg_roi_g2_0_53___xml_to_ytvis_"></a>
## ext_reorg_roi_g2_0_53       @ xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 subseq=1 subseq_split_ids=38
__max_length-2__
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 max_length=2

<a id="incremental___ext_reorg_roi_g2_0_53_xml_to_ytvis_"></a>
### incremental       @ ext_reorg_roi_g2_0_53/xml_to_ytvis-->coco
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 subseq=1 subseq_split_ids=38 incremental=1
__max_length-2__
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 incremental=1 max_length=2
__max_length-10__
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 subseq=1 subseq_split_ids=38 incremental=1 max_length=10
__max_length-20__
python3 xml_to_ytvis.py root_dir=/data/ipsc/well3/all_frames_roi seq_paths=ext_reorg_roi.txt class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt start_frame_id=0 end_frame_id=53 ignore_invalid_label=1 val_ratio=0 allow_missing_images=0 get_img_stats=0 description=ipsc-ext_reorg_roi_g2_0_53 save_masks=0 n_proc=12 subseq=1 subseq_split_ids=38 incremental=1 max_length=20

<a id="coco_to_xml_"></a>
# coco_to_xml

<a id="all_frames_roi_g2_0_37___coco_to_xm_l_"></a>
## all_frames_roi_g2_0_37       @ coco_to_xml-->coco

<a id="swi___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### swi       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swin_det/ipsc_2_class_all_frames_roi_g2_0_37/g2_38_53/results.segm.json  gt_json=all_frames_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt save_csv=1

python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swin_det/ipsc_2_class_all_frames_roi_g2_0_37/g2_38_53/results.segm.json  gt_json=ytvis19/ytvis-ipsc-all_frames_roi_g2_38_53_coco.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt

<a id="idol___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### idol       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-all_frames_roi_g2_0_37/inference/results.json  gt_json=ytvis-ipsc-all_frames_roi_g2_38_53-.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1

<a id="seqformer___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### seqformer       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-all_frames_roi_g2_0_37/inference/results.json  gt_json=ytvis-ipsc-all_frames_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1

<a id="vita_swin___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### vita-swin       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-all_frames_roi_g2_0_37_swin/inference/results.json  gt_json=ytvis-ipsc-all_frames_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1

<a id="vita_r50___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### vita-r50       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-all_frames_roi_g2_0_37_r50/inference/results.json  gt_json=ytvis-ipsc-all_frames_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1

<a id="vita_r101___all_frames_roi_g2_0_37_coco_to_xml_"></a>
### vita-r101       @ all_frames_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-all_frames_roi_g2_0_37_r101/inference/results.json  gt_json=ytvis-ipsc-all_frames_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1


<a id="ext_reorg_roi_g2_0_37___coco_to_xm_l_"></a>
## ext_reorg_roi_g2_0_37       @ coco_to_xml-->coco
<a id="swi___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### swi       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt 
<a id="nms___swi_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
#### nms       @ swi/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="swi_no_validate_rcnn___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### swi-no_validate-rcnn       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-rcnn/g2_38_53/results.bbox.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12 enable_mask=0 save=0

<a id="swi_no_validate_rcnn_win7___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### swi-no_validate-rcnn-win7       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-rcnn-win7/g2_38_53/results.bbox.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12 enable_mask=0 save=0

<a id="swi_rcnn_win7___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### swi-rcnn-win7       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-rcnn-win7/g2_38_53/results.bbox.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12 enable_mask=0 save=0

<a id="cvnxt_base___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### cvnxt-base       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-convnext_base_in22k/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt 
<a id="nms___cvnxt_base_ext_reorg_roi_g2_0_37_coco_to_xml_"></a>
#### nms       @ cvnxt-base/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-no_validate-convnext_base_in22k/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="cvnxt_large___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### cvnxt-large       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt 
<a id="nms___cvnxt_large_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
#### nms       @ cvnxt-large/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_0_37-convnext_large_in22k/g2_38_53/results.segm.json  gt_json=ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="idol___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### idol       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference/json_results  gt_json=ipsc-ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0

<a id="idol_incremental___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### idol-incremental       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/json_results  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1
__nms__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/json_results  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="probs___idol_incremental_ext_reorg_roi_g2_0_37_coco_to_xml_"></a>
#### probs       @ idol-incremental/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1
__nms__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_0_37/inference_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="seqformer___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### seqformer       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=1

<a id="seqformer_incremental___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### seqformer-incremental       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1
<a id="nms___seqformer_incremental_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
#### nms       @ seqformer-incremental/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_38_53-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="probs___seqformer_incremental_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
#### probs       @ seqformer-incremental/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_0_37/inference_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1

<a id="vita_swin___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### vita-swin       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_0_37_swin/inference/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0

<a id="incremental___vita_swin_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
#### incremental       @ vita-swin/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_0_37_swin/inference_38_53-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1
<a id="nms___incremental_vita_swin_ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
##### nms       @ incremental/vita-swin/ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_0_37_swin/inference_38_53-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="vita_r50___ext_reorg_roi_g2_0_37_coco_to_xm_l_"></a>
### vita-r50       @ ext_reorg_roi_g2_0_37/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_0_37_r50/inference/results.json  gt_json=ipsc-ext_reorg_roi_g2_38_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 eval=0

<a id="ext_reorg_roi_g2_16_53___coco_to_xm_l_"></a>
## ext_reorg_roi_g2_16_53       @ coco_to_xml-->coco

<a id="yl8___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### yl8       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
__last__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53/last/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0
__best__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53/best/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0
<a id="val___yl8_ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
#### val       @ yl8/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
__last__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53-val/last/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0
__best__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53-val/best/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0

<a id="seq_val___yl8_ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
#### seq-val       @ yl8/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
__last__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53-seq-val/last/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0
__best__
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_16_53-seq-val/best/predictions.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0:0.9:0.1 n_proc=12 save=0

<a id="swi___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### swi       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_16_53-no_validate/g2_0_15/results.segm.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="swi_rcnn___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### swi-rcnn       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_16_53-no_validate-rcnn/g2_0_15/results.bbox.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12 enable_mask=0 save=0

<a id="cvnxt___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### cvnxt       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_16_53-convnext_large_in22k/g2_0_15/results.segm.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="idol___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### idol       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=1

<a id="probs___idol_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### probs       @ idol/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0

<a id="idol_inc___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### idol-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1

<a id="nms___idol_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### nms       @ idol-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="idol_inc_probs___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### idol-inc-probs       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="nms_01___idol_inc_probs_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### nms-01       @ idol-inc-probs/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_16_53/inference_model_0254999_incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0.01

<a id="seqformer___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### seqformer       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0
<a id="probs___seqformer_ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
#### probs       @ seqformer/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0

<a id="seqformer_inc___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### seqformer-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1

<a id="nms___seqformer_inc_ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
#### nms       @ seqformer-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="probs___seqformer_inc_ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
#### probs       @ seqformer-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_16_53/inference_model_0241999_incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1

<a id="vita___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### vita       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
<a id="0119999___vita_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0119999       @ vita/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0119999/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0
<a id="0329999___vita_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0329999       @ vita/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0

<a id="vita_inc___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### vita-inc       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
<a id="0119999___vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0119999       @ vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0119999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1
<a id="0329999___vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0329999       @ vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=1 incremental=1
<a id="nms___0329999_vita_inc_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
##### nms       @ 0329999/vita-inc/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin/inference_model_0329999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="vita_inc_retrain___ext_reorg_roi_g2_16_53_coco_to_xml_"></a>
### vita-inc-retrain       @ ext_reorg_roi_g2_16_53/coco_to_xml-->coco
<a id="0004999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0004999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0004999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1
<a id="0079999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0079999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0079999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1
<a id="0104999___vita_inc_retrain_ext_reorg_roi_g2_16_53_coco_to_xm_l_"></a>
#### 0104999       @ vita-inc-retrain/ext_reorg_roi_g2_16_53/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_16_53_swin_retrain/inference_model_0104999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1

<a id="ext_reorg_roi_g2_54_126___coco_to_xm_l_"></a>
## ext_reorg_roi_g2_54_126       @ coco_to_xml-->coco

<a id="yl8___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### yl8       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=yl8/ext_reorg_roi_g2_54_126/last/predictions.json  gt_json=ext_reorg_roi_g2_0_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12

<a id="swi___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### swi       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-no_validate/g2_0_53/results.segm.json  gt_json=ext_reorg_roi_g2_0_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=12
<a id="g2_0_15___swi_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
#### g2_0_15       @ swi/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-no_validate/g2_0_15/results.segm.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=2

<a id="cvnxt_large___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### cvnxt-large       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_large_in22k/g2_0_53/results.segm.json  gt_json=ext_reorg_roi_g2_0_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=1
<a id="g2_0_15___cvnxt_large_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
#### g2_0_15       @ cvnxt-large/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_large_in22k/g2_0_15/results.segm.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=2

<a id="cvnxt_base___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### cvnxt-base       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_base_in22k/g2_0_53/results.segm.json  gt_json=ext_reorg_roi_g2_0_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=2
<a id="g2_0_15___cvnxt_base_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_15       @ cvnxt-base/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi json=swi/ipsc_2_class_ext_reorg_roi_g2_54_126-convnext_base_in22k/g2_0_15/results.segm.json  gt_json=ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt nms_thresh=0.1:0.9:0.1 n_proc=2

<a id="idol_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### idol-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
<a id="g2_0_53___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_53       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### max_length-2       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_max_length-2-incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_53-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_15       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_g2_0_15-incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=2
<a id="max_length_2___idol_inc_ext_reorg_roi_g2_54_126_coco_to_xml__1"></a>
#### max_length-2       @ idol-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/idol-ipsc-ext_reorg_roi_g2_54_126/inference_model_0596999_g2_0_15-max_length-2-incremental_probs/json_results  gt_json=ipsc-ext_reorg_roi_g2_0_15-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 fix_category_id=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="seqformer_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### seqformer-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
<a id="g2_0_53___seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
#### g2_0_53       @ seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999-incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=2
<a id="max_length_2___g2_0_53_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
##### max_length-2       @ g2_0_53/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_max_length-2-incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_10___g2_0_53_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
##### max_length-10       @ g2_0_53/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_max_length-10-incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-max_length-10-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
#### g2_0_15       @ seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_g2_0_15-incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=2
<a id="max_length_2___g2_0_15_seqformer_inc_ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
##### max_length-2       @ g2_0_15/seqformer-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vnxt/seqformer-ipsc-ext_reorg_roi_g2_54_126/inference_model_0495999_g2_0_15-max_length-2-incremental_probs/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="vita___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### vita       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
<a id="g2_0_53___vita_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_53       @ vita/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___g2_0_53_vita_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
##### max_length-2       @ g2_0_53/vita/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_max_length-2/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-max_length-2.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___vita_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_15       @ vita/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___g2_0_15_vita_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
##### max_length-2       @ g2_0_15/vita/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-max_length-2/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-max_length-2.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 nms_thresh=0:0.9:0.1 n_proc=12

<a id="vita_inc___ext_reorg_roi_g2_54_126_coco_to_xm_l_"></a>
### vita-inc       @ ext_reorg_roi_g2_54_126/coco_to_xml-->coco
<a id="g2_0_53___vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_53       @ vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12
<a id="max_length_2___g2_0_53_vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
##### max_length-2       @ g2_0_53/vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_max_length-2-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_53-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="g2_0_15___vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
#### g2_0_15       @ vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=2
<a id="max_length_2___g2_0_15_vita_inc_ext_reorg_roi_g2_54_126_coco_to_xml_"></a>
##### max_length-2       @ g2_0_15/vita-inc/ext_reorg_roi_g2_54_126/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/ipsc/well3/all_frames_roi/ytvis19 json=vita/vita-ipsc-ext_reorg_roi_g2_54_126_swin/inference_model_0194999_g2_0_15-max_length-2-incremental/results.json  gt_json=ipsc-ext_reorg_roi_g2_0_15-max_length-2-incremental.json class_names_path=../labelling_tool/data/predefined_classes_ipsc_2_class.txt ytvis=1 save=0 incremental=1 nms_thresh=0:0.9:0.1 n_proc=12

<a id="db3_2_to_17_except_6___coco_to_xm_l_"></a>
## db3_2_to_17_except_6       @ coco_to_xml-->coco

<a id="idol___db3_2_to_17_except_6_coco_to_xml_"></a>
### idol       @ db3_2_to_17_except_6/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/mojow_rock/rock_dataset3/ytvis19 json=vnxt/idol-ytvis-mj_rock-db3_2_to_17_except_6_large_huge/inference/json_results  gt_json=mj_rock-september_5_2020-large_huge-max_length-50.json class_names_path=../labelling_tool/data/predefined_classes_rock.txt ytvis=1 eval=0 fix_category_id=1 nms_thresh=0

<a id="vita___db3_2_to_17_except_6_coco_to_xml_"></a>
### vita       @ db3_2_to_17_except_6/coco_to_xml-->coco
<a id="r50___vita_db3_2_to_17_except_6_coco_to_xm_l_"></a>
#### r50       @ vita/db3_2_to_17_except_6/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/mojow_rock/rock_dataset3/ytvis19 json=vita/db3_2_to_17_except_6-vita_r50/inference/results.json  gt_json=mj_rock-september_5_2020-large_huge-max_length-200.json class_names_path=../labelling_tool/data/predefined_classes_rock.txt ytvis=1 eval=0 fix_category_id=0 nms_thresh=0

<a id="r101___vita_db3_2_to_17_except_6_coco_to_xm_l_"></a>
#### r101       @ vita/db3_2_to_17_except_6/coco_to_xml-->coco
python3 coco_to_xml.py root_dir=/data/mojow_rock/rock_dataset3/ytvis19 json=vita/db3_2_to_17_except_6-vita_r101/inference/results.json  gt_json=mj_rock-september_5_2020-large_huge-max_length-200.json class_names_path=../labelling_tool/data/predefined_classes_rock.txt ytvis=1 eval=0 fix_category_id=0 nms_thresh=0
