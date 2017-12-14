# WRAP - An open model for operational aircraft performance and flight envelope
As part of an open aircraft performance modeling project, the WRAP database provides operational and limitation values of aircraft performance parameters. Common aircraft types are included.

ADS-B data are use for model construction. Each parameters are constructed based on at least 5000 flight of same aircraft type. Detailed methods and model description can be found in **paper.pdf** 

## Parameters

  * **Take-off**: to_acc_tof, to_d_tof, to_v_lof
  * **Initial climb**: ic_va_avg, ic_va_std, ic_vh_avg, ic_vh_std
  * **Climb**: cl_d_range, cl_h_cas_const, cl_h_mach_const, cl_v_cas_const, cl_v_mach_const, cl_vh_avg_cas_const, cl_vh_avg_mach_const, cl_vh_avg_pre_cas
  * **Cruise**: cr_d_range, cr_h_max, cr_h_mean, cr_v_cas_max, cr_v_cas_mean, cr_v_mach_max, cr_v_mach_mean
  * **Descent**: de_d_range, de_h_cas_const, de_h_mach_const, de_v_cas_const, de_v_mach_const, de_vh_avg_after_cas, de_vh_avg_cas_const, de_vh_avg_mach_const
  * **Final pproach**: fa_va_avg, fa_va_std, fa_vh_avg, fa_vh_std
  * **Landing**: ld_acc_brk, ld_d_brk, ld_v_app

## Aircraft types
  * Airbus aircraft
    * A319, A320, A321, A332, A333, A343, A388
  * Boeing aircraft
    * B737, B738, B739, B744, B752, B763, B77W, B788, B789
  * Other aircraft
    * E190
