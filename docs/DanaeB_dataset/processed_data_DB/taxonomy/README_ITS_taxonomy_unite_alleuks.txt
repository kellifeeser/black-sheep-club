ITS taxonomy

ref db: 
Title		UNITE USEARCH/UTAX release for eukaryotes
Location	https://dx.doi.org/10.15156/BIO/2938084
Published	2023
Creators	Abarenkov, Kessy; Zirk, Allan; Piirmann, Timo; Pöhönen, Raivo; Ivanov, Filipp; Nilsson, R. Henrik; Kõljalg, Urmas.
Date Created	2023-07-18
Date updated	2023-07-25
Date downloaded	2023-08-11
Abstract	Reference file for USEARCH/UTAX. For optimized parameters and further information, please refer to the UTAX UNITE page. 
		This is the "dynamic" release of the UNITE species hypotheses system, with singleton species hypotheses included. Any parts of the 18S and 28S are left in these sequences.
		This reference file can be used for ITS1-only or ITS2-only sequences if parameters trained on ITS1 or 2 only ('taxconfs' files) are used. ITS regions can be extracted using the ITSx tool.
Citation	Abarenkov, Kessy; Zirk, Allan; Piirmann, Timo; Pöhönen, Raivo; Ivanov, Filipp; Nilsson, R. Henrik; Kõljalg, Urmas (2023): UNITE USEARCH/UTAX release for eukaryotes. UNITE Community. 10.15156/BIO/2938084
File name	utax_reference_dataset_all_25.07.2023.fasta

Version no	9.0
Release date	2023-07-18
Taxon group	All eukaryotes
No of seqs	326 727

######
#making sintax format
#$ usearch -makeudb_usearch unite_general_release_dynamic_s_all_18.07.2023.fasta -output unite_alleuk_18.07.2023.udb
#####