* name: warmup
* start date: Fri Nov 20 12:05:53 EST 2015
* description
* files
** input/
    `-- toy.tsv
** output/
*** toy1.tsv
    generated with

    % src/add_gr_column.py input/toy.tsv > output/toy1.tsv

** NOTES.org
* software
** src/add_gr_column.py

    Usage:

    add_gr_column.py input.tsv > output.tsv

    input.tsv must

    - have column headers in the first row
    - contain numeric columns with headers cell_count, cell_count__ctrl, and
      cell_count__time0