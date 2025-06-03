
Chemotion Converter
===================


Chemotion Converter is a very powerful python file converter running as a stand-alone flask server or included in an ELN and called via API during file upload. For local and offline users, it is also possible to use it as an CLI tool.
# Profiles
  

|id|reader|extension|title|description|devices|software|identifiers|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|0cd6596c-83d2-49ab-a982-1dfec98d16ba|CSVReader|.dpt|IR DPT|IR-Alpha (CS)|[]|[]|[('extension', '.dpt')]|
|0d04f3c5-43d4-408a-85ef-34b33975020a|CSVReader|.csv|DSC with Time|differential scanning calorimetry|[]|[]|[('reader', 'CSVReader'), ('extension', '.csv'), ('column_02', 'DSC/(mW/mg)'), ('column_00', '##Temp./°C')]|
|0d7dd8d4-a599-4151-855e-643956a7362c|BrmlReader|.brml|X-ray diffraction data from brml, data: +, metadata: -|---; ref location: ---, data: +, metadata: -|[]|[]|[('extension', '.brml')]|
|15400217-b730-47db-9d5c-a300bce7ae95|ExcelReader|.xlsx|UVVIS CS|multicolumn (2) XLSX file with header at the end - Data from Tasnim|[]|[]|[('reader', 'ExcelReader'), ('extension', '.xlsx')]|
|2a913039-c48d-4fd5-9fbb-706733e53f76|CSVReader|.txt|UV-Vis|UV Vis INT (FI)|[]|[]|[('reader', 'CSVReader')]|
|3e2fb90e-b6b6-4152-9182-ed8e203a58b5|CSVReader|.csv|DSC without time|differential scanning calorimetry|[]|[]|[('reader', 'CSVReader'), ('column_01', 'DSC/(mW/mg)'), ('column_00', '##Temp./°C'), ('extension', '.csv')]|
|44f5bfbb-ae1f-4da0-b43b-0d33b649c24a|SecReader|.TXT|SEC 1|Size Exclusion Chromatography (SEC)<br>with one Detector Output|[]|[]|[('reader', 'SecReader'), ('table_name', 'MWD'), ('Detector 1', 'I1')]|
|5a413afd-cb77-40e4-99b1-c044d94eaa51|CSVReader|.txt|UV-VIS data from general txt, data: +, metadata: -|generic data table only; ref location: ---, data: +, metadata: -|[]|[]|[]|
|5b206281-49f6-437b-99ca-c64a621eb903|AsciiReader|.xy|Mass spectrometry from general xy format, data: +, metadata: -|generic data table only; ref location: Uni Aachen, data: +, metadata: -|[]|[]|[]|
|5cb879d1-2b3f-4778-8e06-1a198500c8db|AifReader|.txt|(AIF) Sorption-Desorption Measurement from txt, data: +, metadata: +|---; ref location: TU Dresden, data: +, metadata: + <br>|[]|[]|[('reader', 'AifReader'), ('Unit_column_#0', '_adsorp_pressure')]|
|6bb4fea5-3a59-4b95-8956-d977a4d8b6a7|NovaReader|.txt|CV data from txt, data: +, metadata: (+)|Metrohm Autolab Nova; ref location: Uni Aachen, data: +, metadata: (-)<br>;(basic Metadata calculation done by Reader)|[]|[]|[('reader', 'NovaReader'), ('column_00', 'Potential applied (V)'), ('column_02', 'WE(1).Current (A)')]|
|6be46fd7-59a2-4b02-829b-cbfef8c19646|CSVReader|.txt|UV-VIS data from txt, data: +, metadata: -|JASCO V-570; ref location: KIT CN, data: +, metadata: +|[]|[]|[('extension', '.txt')]|
|6d344bc4-c4fb-4306-9d56-1e754e7e0590|CSVReader|.txt|Tensile test data from txt, data: +, metadata: -|Inspect Table 50kN; ref location: Fraunhofer IWS, data: +, metadata: -<br>;LowTemp|[]|[]|[('column_01', 'Force_N'), ('column_05', 'Elongation_%'), ('column_02', 'Strain_mm')]|
|71883827-4472-48d8-becf-64ea89324f3e|SecReader|.TXT|SEC 2|Size Exclusion Chromatography with two Detector Outputs|[]|[]|[('reader', 'SecReader'), ('table_name', 'MWD'), ('Detector 2', 'I2')]|
|799f3db4-fd21-4aa7-a7bd-7c5548cbe316|DtaReader|.DTA|CV Gamry||[]|[]|[('extension', '.DTA'), ('TITLE', 'Cyclic')]|
|8079b064-6314-4d99-b13b-e4f590cf556f|CSVReader|.csv|UV-VIS data from csv, data: +, metadata: -|Cary 60; ref location: KIT CN, data: +, metadata: +|[]|[]|[('column_00', 'Wavelength'), ('column_01', 'Abs')]|
|a5b05507-aed2-462b-a526-3fee53c87a48|CSVReader|.txt|DLS data from txt, data: +, metadata: -|---; ref location: ---, data: +, metadata: -<br>;Subtype 1|[]|[]|[('file_name', 'SSP-0'), ('extension', '.txt')]|
|af891148-ebcc-4e5d-a481-fa6acc853699|CSVReader|.txt|UV-VIS data from txt, data: +, metadata: -|Horiba Duetta; ref location: KIT CN, data: +, metadata: +|[]|[]|[]|
|b31ef3df-eacf-4440-bbb3-34b073be9eb9|CSVReader|.txt|CD MS Spectra data from txt, data: +, metadata: -|LCMSsolution; ref location: KIT CN, data: +, metadata: + ;Subtype 2|[]|[]|[('reader', 'CSVReader')]|
|c498c925-61e0-455e-a4c6-c46ac9c2f5c6|CSVReader|.csv|Mass spectrometry from txt, data: +, metadata: -|Finnigian MAT8230, ref location: ---, data: +, metadata: -|[]|[]|[]|
|c6573972-cb06-484d-a529-9dd2424fc408|PsSessionReader|.pssession|CV data from pssession, data: +, metadata: +|PalmSens PSTrace; ref location: IPB Leibniz, data: +, metadata: +|[]|[]|[('extension', '.pssession'), ('title', '(Cyclic Voltammetry)')]|
|c7e3130f-6c23-432a-a886-a82d11632da2|CSVReader|.txt|UV-Vis|UV-Vis (AK Théato Seminar) - Campus West, KIT|[]|[]|[('reader', 'CSVReader')]|
|c9d63af9-2ce7-425e-895c-c04b8497c26c|CSVReader|.txt|Tensile test data from txt, data: +, metadata: -|Inspect Table 50kN; ref location: Fraunhofer IWS, data: +, metadata: - <br>;HighTemp|[]|[]|[('column_01', 'Force_N'), ('column_02', 'Deformation (fine)_mm'), ('column_05', 'Strain_mm')]|
|cddfe1ff-ef5a-44fb-a6ba-443a870c7a27|CSVReader|.txt|Emission spectrum|(fluorescence) emission spectrum with generic dataset (FI)|[]|[]|[('reader', 'CSVReader')]|
|d8e6bf8f-6de1-4743-9513-04cbd0c6c712|CSVReader|.csv|UVVIS CS|multicolumn (4) file with no header - Data from Tasnim|[]|[]|[('reader', 'CSVReader'), ('extension', '.csv'), ('column_00', 'Wavelength (nm)'), ('column_07', 'Abs')]|
|d9be2928-fd8e-4abe-bbe0-3e419330875f|CSVReader|.txt|DLS data from txt, data: +, metadata: -|---; ref location: ---, data: +, metadata: -<br>;Subtype 2|[]|[]|[('extension', '.txt'), ('file_name', 'IW-SPEGA')]|
|db05bfb4-6829-4339-bec1-54065710f211|CSVReader|.csv|UV-VIS data from multi-column csv, data: +, metadata: -|Cary 60; ref location: KIT CN, data: +, metadata: +|[]|[]|[('content_type', 'text/csv')]|
|df15f2b0-4133-4231-8b48-bec52fb6043c|CifReader|.cif|crystallographic metadata from cif, data: -, metadata: +|Stoe StadiVari diffractometer; ref location: KIT CN, data: +, metadata: +|[]|[]|[('extension', '.cif'), ('reader', 'CifReader')]|
|e10cd71e-b44f-4493-b7ad-ca231ccd324f|ExcelReader|.xlsx|DLS|DLS intensity INT (FI)|[]|[]|[('reader', 'ExcelReader')]|
|e7a4ee04-cdf6-4da6-a82c-ba6909af6cee|OldExcelReader|.xls|TGA|TGA - Campus West, KIT with Isothermal|[]|[]|[('reader', 'OldExcelReader'), ('Instrument Type', 'TGA5500')]|
|e845bc85-07b9-4e21-8bdf-4daa4a74fa15|OldExcelReader|.xls|TGA with derivative|TGA - Campus West, KIT with Isothermal<br>and Derivative|[]|[]|[('reader', 'OldExcelReader'), ('Instrument Type', 'TGA5500')]|
|fb19f78e-8d87-4c5f-a4e1-ac90994300d7|CSVReader|.txt|CD MS Spectra data from txt, data: +, metadata: -|LCMSsolution; ref location: KIT CN, data: +, metadata: +<br>;Subtype 1|[]|[]|[('reader', 'CSVReader'), ('column_00', 'm/z')]|
|fb63e718-3842-4d45-9b39-84a53b27e483|OldExcelReader|.xls|TGA 2|TGA - Campus West, KIT without Isothermal|[]|[]|[('reader', 'OldExcelReader'), ('Instrument Type', 'TGA5500')]|
|fbbe088a-b688-4609-8c00-086a149f61ba|ExcelReader|.xlsx|DLS-ACF|ACF - INT (FI)|[]|[]|[('reader', 'ExcelReader')]|
