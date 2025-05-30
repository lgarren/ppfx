set(SUBDIR "1")
install( FILES
          ${SUBDIR}/invxs_kam_FTFP_BERT.root
          ${SUBDIR}/invxs_kap_FTFP_BERT.root
          ${SUBDIR}/invxs_klong_FTFP_BERT.root
          ${SUBDIR}/invxs_kshort_FTFP_BERT.root
          ${SUBDIR}/invxs_pim_FTFP_BERT.root
          ${SUBDIR}/invxs_pip_FTFP_BERT.root
          ${SUBDIR}/invxs_prt_FTFP_BERT.root
          ${SUBDIR}/invxs_qe_corr_prt.root
          ${SUBDIR}/neu_FTFP_BERT.root
          ${SUBDIR}/prt_FTFP_BERT.root
          ${SUBDIR}/qe_corr_neu.root
          ${SUBDIR}/qe_corr_nucl.root
          ${SUBDIR}/yield_neu_FTFP_BERT.root
          ${SUBDIR}/yield_qe_corr_neu.root
         DESTINATION data/MC/FTFP )
