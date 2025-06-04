# files_for_CEH_portal
Files for CEH nowcasting portal

trained models and notebook for reatime prediction

1) Models for Zambia and Kenya are trained on the native MSG resolution, while the model for senegal is trained on a regular 0.04 degree grid.
2) The TIR used for all domains and lead times is the same (TIR MSG)
3) Every leadtime has it's own trained model
4) When predicting, it is important to use the correct lead time, domain, and grid.
5) A few parameters define domain (and grid) specific features (a, b, lat_i, lon_i)
