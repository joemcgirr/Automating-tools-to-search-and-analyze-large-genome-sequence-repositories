# Automating-tools-to-search-and-analyze-large-genome-sequence-repositories

## Motivation
As more strains of hCoV-19 are sequenced, various tools have been developed to monitor how it spreads and evolves. However, many sequences are not yet publicly available. Our goal is to combine publicly available hCoV-19 SRA sequences with the Nextstrain tool (https://github.com/nextstrain/ncov).

## Analyzing publicly available hCoV-19 SRA reads with Nextstrain
1. Identify metadata to match Nexstrain input
2. Download SRA data
3. Align reads to Wuhan reference genome
4. Run Nextstrain for analyses and visualization

## 1. Metadata
Identify hCoV-19 SRA reads and wrangle metadta to create Nextstrain metadata.tsv 
metadata.tsv contains: strain	virus	gisaid_epi_isl	genbank_accession	date	region	country	division	division_exposure	location	segment	length	host	age	sex	originating_lab	submitting_lab	authors	url	title

## 2. Download SRA data
download hCoV-19 SRA reads to vm

## 3. Align reads to Wuhan reference genome
with bwa mem

## 4. Run Nextstrain for analyses and visualization
run snakemake
