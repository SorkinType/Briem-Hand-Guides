# Briem Hand

[![][Fontbakery]](https://EbenSorkin.github.io/Briem-Hand/fontbakery/fontbakery-report.html)
[![][Universal]](https://EbenSorkin.github.io/Briem-Hand/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://EbenSorkin.github.io/Briem-Hand/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://EbenSorkin.github.io/Briem-Hand/fontbakery/fontbakery-report.html)
[![][Shaping]](https://EbenSorkin.github.io/Briem-Hand/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEbenSorkin%2FBriem-Hand%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEbenSorkin%2FBriem-Hand%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEbenSorkin%2FBriem-Hand%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEbenSorkin%2FBriem-Hand%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEbenSorkin%2FBriem-Hand%2Fgh-pages%2Fbadges%2FUniversal.json

Briem Hand is one of two related font families. This one offers an unusually realistic set of join strokes between the letters which join in handwritten text. The other, Briem Print, keeps each letter separate and not joined. Both designs help teach the handwriting system made by Gunnlaugur SE Briem.

See Briem Print: [https://github.com/SorkinType/Briem-Print](https://github.com/SorkinType/Briem-Print)

*Note! In Adobe InDesign 2020 need to have preferences in Advanced Type set to "world ready single line composer" or "Adobe World-Ready paragraph composer" * Other Adobe products may require a similar intervention.

![Sample Image](documentation/image1a.png)

## About

Gunnlaugur SE Briem is a designer and lives in Spain. His postgraduate studies in Basel and London ended with a PhD from the Royal College of Art. Gunnlaugur SE Briem designed Briem Print. 

Versions of this design idea with less language support and without variable font versions have been released under other font names in the past by Microsoft, Adobe and Monotype.

Sorkin Type Co. is a Massachusetts based font foundry.


## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://sorkintype.github.io/Briem-Hand/.

## Changelog

**16 October 2022. Version 1.01**
- MAJOR Font turned to a variable font.
- SIGNIFICANT Kerning added
- SIGNIFICANT Eight interpolated weights instead of two weights
- SIGNIFICANT New lamguage support, additional punctuation, symbols and joining suppport for all of the weights.

**11 Feb 2022 Version Version 1.02**
- SIGNIFICANT New lamguage support, symbols and joining suppport for the new letters, aditional kerning, new support for dotted circle, Resoration of 'z' writing support pattern, interpolation corrections.



Hyperglot says Briem Hand supports 516 languages out of 533 possible in the Latin script:
------------------------------
Abidji, Abron, Abua, Acheron, Achinese, Acholi, Achuar-Shiwiar, Adamawa Fulfulde, Adangme, Adele, Afar, Afrikaans, Aghem, Agni, Aguaruna, Ahanta, Ahtna, Aja (Benin), Akebu, Akoose, Alekano, Aleut, Amahuaca, Amarakaeri, Amis, Anaang, Andaandi, Dongolawi, Angas, Anii, Anufo, Anuta, Ao Naga, Apinay??, Arabela, Aragonese, Arb??resh?? Albanian, Arvanitika Albanian, Ash??ninka, Ash??ninka Peren??, Asturian, Asu (Tanzania), Atayal, Avatime, Awa-Cuaiquer, Awet??, Awing, Ayizo Gbe, Baatonum, Bafia, Bagirmi Fulfulde, Balante-Ganja, Balinese, Balkan Romani, Bambara, Baoul??, Bari, Basque, Bassari, Batak Dairi, Batak Karo, Batak Mandailing, Batak Simalungun, Batak Toba, Bemba (Zambia), Bena (Tanzania), Biali, Bikol, Bini, Bislama, Bissa, Boko (Benin), Bomu, Bora, Borana-Arsi-Guji Oromo, Borgu Fulfulde, Bosnian, Bouna Kulango, Breton, Buamu, Buginese, Bushi, Candoshi-Shapra, Caquinte, Caribbean Hindustani, Cashibo-Cacataibo, Cashinahua, Catalan, Cebuano, Central Aymara, Central Kurdish, Central Mazahua, Central Nahuatl, Central-Eastern Niger Fulfulde, Cerma, Chachi, Chamorro, Chavacano, Chayahuita, Chickasaw, Chiga, Chiltepec Chinantec, Chokwe, Chuukese, Cimbrian, Cof??n, Congo Swahili, Cook Islands M??ori, Cornish, Corsican, Creek, Crimean Tatar, Croatian, Czech, Dagbani, Danish, Dehu, Dendi (Benin), Dimli, Dinka, Ditammari, Duala, Dutch, Dyan, Dyula, Eastern Abnaki, Eastern Arrernte, Eastern Maninkakan, Eastern Oromo, Efik, Embu, English, Ese Ejja, Ewe, Ewondo, Falam Chin, Fanti, Farefare, Faroese, Fe'Fe', Fijian, Filipino, Finnish, Fon, Foodo, French, Friulian, Ga, Gagauz, Galician, Ganda, Garifuna, Ga???anda, Gen, German, Gheg Albanian, Gilbertese, Gonja, Gooniyandi, Gourmanch??ma, Guadeloupean Creole French, Guinea Kpelle, Gusii, Gwich??in, Haitian, Hakha Chin, Hani, Hassaniyya, Hausa, Hawaiian, Hiligaynon, Ho-Chunk, Hopi, Huastec, Hungarian, H??n, Ibibio, Icelandic, Idoma, If??, Igbo, Iloko, Inari Sami, Indonesian, Irish, Istro Romanian, Italian, Ixcatl??n Mazatec, Jamaican Creole English, Japanese, Javanese, Jenaama Bozo, Jola-Fonyi, K'iche', Kabiy??, Kabuverdianu, Kabyle, Kaingang, Kako, Kala Lagaw Ya, Kalaallisut, Kalenjin, Kamba (Kenya), Kanuri, Kaonde, Kaqchikel, Kara-Kalpak, Karelian, Karo, Kasem, Kashubian, Kekch??, Kenzi, Mattokki, Khasi, Kikuyu, Kimbundu, Kinyarwanda, Kirmanjki, Kituba (DRC), Kom (Cameroon), Kongo, Konzo, Koonzime, Koyra Chiini Songhay, Koyraboro Senni Songhai, Krio, Kuanyama, Kusaal, Kven Finnish, Kwasio, K??lsch, Ladin, Ladino, Lakota, Lama, Lamnso', Langi, Latgalian, Latin, Ligurian, Lingala, Lithuanian, Lobi, Lombard, Low German, Lower Sorbian, Lozi, Luba-Katanga, Luba-Lulua, Lukpa, Lule Sami, Luo (Kenya and Tanzania), Luxembourgish, Lyele, L???? L???? Bwamu, Maasina Fulfulde, Macedo-Romanian, Madurese, Makhuwa, Makhuwa-Meetto, Makonde, Makwe, Malagasy, Malaysian, Malba Birifor, Maltese, Mam, Mamara Senoufo, Mandinka, Mandjak, Mankanya, Manx, Maore Comorian, Maori, Mapudungun, Marshallese, Masai, Masana, Mats??s, Mauritian Creole, Mbelime, Medumba, Megleno Romanian, Mende (Sierra Leone), Meriam Mir, Meru, Meta???, Metlat??noc Mixtec, Mezquital Otomi, Mi'kmaq, Minangkabau, Mirandese, Miyobe, Mizo, Moba, Mohawk, Montenegrin, Mossi, Mundang, Munsee, Murrinh-Patha, Murui Huitoto, Muslim Tat, Mwani, M??nik, M??skito, Naga Pidgin, Nateni, Navajo, Nawdm, Ndonga, Ndrulo, Neapolitan, Ngazidja Comorian, Ngiemboon, Ngomba, Nigerian Fulfulde, Niuean, Nobiin, Nomatsiguenga, Noon, North Azerbaijani, North Marquesan, North Ndebele, Northeastern Dinka, Northern Bobo Madar??, Northern Dagara, Northern Kissi, Northern Kurdish, Northern Qiandong Miao, Northern Sami, Northern Uzbek, Norwegian, Nuer, Nyamwezi, Nyanja, Nyankole, Nyemba, Nzima, Occitan, Ojitl??n Chinantec, Orma, Oroqen, Otuho, Palauan, Paluan, Pampanga, Papantla Totonac, Papiamento, Paraguayan Guaran??, Pedi, Phuie, Picard, Pichis Ash??ninka, Piemontese, Pijin, Pintupi-Luritja, Pipil, Pite Sami, Pohnpeian, Polish, Portuguese, Potawatomi, Prussian, Pulaar, Pular, Purepecha, P??ez, Quechua, Romanian, Romansh, Rotokas, Rundi, Rwa, Saafi-Saafi, Samburu, Samoan, Sango, Sangu (Tanzania), Saramaccan, Sardinian, Saxwe Gbe, Scottish Gaelic, Secoya, Sena, Serer, Seri, Seselwa Creole French, Shambala, Sharanahua, Shawnee, Shilluk, Shipibo-Conibo, Shona, Shuar, Sicilian, Silesian, Siona, Sissala, Skolt Sami, Slovak, Slovenian, Soga, Somali, Soninke, South Azerbaijani, South Marquesan, South Ndebele, Southern Aymara, Southern Bobo Madar??, Southern Dagaare, Southern Nuni, Southern Qiandong Miao, Southern Sami, Southern Samo, Southern Sotho, Spanish, Sranan Tongo, Standard Estonian, Standard Latvian, Standard Malay, Sundanese, Susu, Swahili, Swati, Swedish, Swiss German, Syenara Senoufo, Tagalog, Tahitian, Taita, Talysh, Tasawaq, Tawallammat Tamajaq, Tedim Chin, Tem, Tetum, Tetun Dili, Ticuna, Tigon Mbembe, Tikar, Timne, Tiv, Ti??yaxo Bozo, Toba, Tojolabal, Tok Pisin, Tokelau, Toma, Tonga (Tonga Islands), Tonga (Zambia), Tosk Albanian, Totontepec Mixe, Tsafiki, Tsakhur, Tsonga, Tswana, Tumbuka, Turka, Turkish, Turkmen, Tuvalu, Twi, Tzeltal, Tzotzil, Uab Meto, Umbundu, Ume Sami, Upper Guinea Crioulo, Upper Sorbian, Urarina, Venda, Venetian, Veps, Vietnamese, Vlax Romani, V??ro, Waama, Waci Gbe, Wallisian, Walloon, Walser, Wamey, Wangaaybuwan-Ngiyambaa, Waorani, Waray (Philippines), Warlpiri, Wasa, Wayuu, Welsh, West Central Oromo, West-Central Limba, Western Abnaki, Western Frisian, Western Niger Fulfulde, Wik-Mungkan, Winy??, Wiradjuri, Wolof, Xav??nte, Xhosa, Xwela Gbe, Yagua, Yanesha', Yangben, Yanomam??, Yao, Yapese, Yindjibarndi, Yom, Yoruba, Yucateco, Zapotec, Zarma, Zulu, Zuni, Z??paro

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
