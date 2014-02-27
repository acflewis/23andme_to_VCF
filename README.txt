Conversion script from 23andme file format to VCF format
________________

23andme gives you your genotype information in a nonstandard file format. Variant Call Format, or VCF, is used by more applications.
Information on the VCF is found here: http://www.1000genomes.org/node/101

TO USE
-- Make sure you have conversion_script.py and the reference file, 23andme_reference_genome.txt.gz, in a directory
-- From that directory, run
 'python conversion_script.py path/to/23andme_input_file.txt path/to/vcf_output_file.vcf'

NOTES
-- Check the reference build your 23andme file used. Currently, these use reference build 37. A new 23andme_reference_genome.txt will be needed if this changes, in which case please contact me.
-- This conversion supports both v3 and v4 of 23andme's chip