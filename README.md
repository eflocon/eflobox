# eflobox
Scalable box design. Inspired by eurobox standard. Optimised for using available materials and cutting services.

## software

openscad

## designfiles



### design/eflobox.scad

file to calculate model, requires data.scad in same dir

 ### design/data.scad
file including design parameters like dimensions of eflobox

### design parameters

These are the main parameter to set dimensions of the box:

- *eb_length*: set outside dimension of box, large side
- *eb_width*: set outside dimension of box, small side
- *eb_height_inner*: set inner height of box
- *eb_in_out_diff*: diff inner outer box boundaries for footers
- *min_cut_width*: local cutting services may demand minimal width for cutting

### output

Openscad -> Console -> "ECHO:" will output count and dimensions of parts to build eflobox

