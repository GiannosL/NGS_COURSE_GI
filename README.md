# Genotype Imputation for NGS
Teaching material for Genotype Imputation lecture in NGS course.

## Basic **BASH** commands
1. `ls <path>` 
    * list the directory contents.
2. `less -S <file>` 
    * show the contents of the file, chop long lines.
3. `head -n <int> <file>` 
    * show the top *int* lines of a file.
4. `grep "pattern" <file>` 
    * show the lines in file that contain pattern.
5. `grep -v "pattern" <file>`
    * show lines in file that do NOT contain pattern.
6. `wc -l <file>` 
    * count lines in file.

## File formats
* **Variant Call Format (VCF)**
    * [Manual](https://samtools.github.io/hts-specs/VCFv4.2.pdf)

* **BED/BIM/FAM files (plink format)**
    * [Plink file formats](https://www.cog-genomics.org/plink/1.9/formats)

## Tools
1. Plink2
    * [Plink homepage](https://www.cog-genomics.org/plink/)
2. Bcftools
    * [Bcftools homepage](https://samtools.github.io/bcftools/bcftools.html)
3. Impute5
    * [J. Marchini software](https://jmarchini.org/software/)
    * [Manual]()