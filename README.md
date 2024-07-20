# cv
CV generated with R

# Code to generate necessary files
use_datadriven_cv(
  full_name = "Simon Müller",
  
  # data_location = system.file("sample_data/", package = "datadrivencv"),
  # data_location = system.file("data/", package = "datadrivencv"),
  data_location = "https://docs.google.com/spreadsheets/d/1urM7Art9-zrZcMjFGS13GDdrg1J1KvnrHFK8Tgtd0bo/edit?usp=sharing",
  
  #pdf_location = "https://github.com/nstrayer/cv/raw/master/strayer_cv.pdf",
  pdf_location = "https://github.com/mosoho/cv/simon_mueller_cv.pdf",
  
  #html_location = "nickstrayer.me/datadrivencv/",
  html_location = "https://sites.google.com/view/simons-portfolio-now/",
  
  #source_location = "https://github.com/nstrayer/datadrivencv",
  source_location = "https://github.com/mosoho/cv",
  
  which_files = "all",
  
  output_dir = getwd(),
  
  create_output_dir = FALSE,
  
  use_network_logo = FALSE,
  
  open_files = TRUE
)
