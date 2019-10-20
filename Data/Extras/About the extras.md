## Extras
Some of my example programs process the output from other programs or apps, or create files for use in my other programs. I encourage users to create these files themselves, and I included the necessary files in the 'Data' folder. The programs save the files they create to the 'Data' folder as well. Most take only seconds to create, but the example output files from running the [TIME web application](https://web.rniapps.net/time/index.php) using their example antibiotic perturbation analysis will take 5-10 minutes to create and download. 

Therefore, to make the repository as accessible as possible, I am providing those files, along with the other files which are created by one of my programs and used as input for others, for your convenience here. I am also including the input I used to create example output for GP Microbiome, to give you an idea of what that consists of. (See also the GitHub repository for [GP Microbiome](https://github.com/tare/GPMicrobiome/blob/master/README.md) for their explanation of the input files and their format.)

In  my programs, when there is an option to use the data in the 'Extras' folder, you will find that I have included the alternative code, either as a separate cell or as a comment in the same cell. The program will direct you to un-comment that line and comment out the one which uses the 'Data' folder. 

### Files related to other programs

#### Box Plot Data (Folder)
These files are for the box plot programs, and are output downloaded from the TIME web application's Workflow 5b.

#### Example GP Microbiome Input Files (Folder)
The input files I used to create the example output pickle file from GP Microbiome, 'example_output.p'.

### Files created by my own programs

#### Relative Abundance Files (Folder)
The files created by the program Create_relative_abundance_files

#### TDTW_all_example.csv
File created by the program Create_TDTW_all_example

#### OTUkey_named.csv
File created by either the program Plotsamples or the program Leave_One_Out_Examples

