OpenDC Hugo website update
============================

# Project keys:

| keys | Project                    |
|------|----------------------------|
| 73   | 0136 Plateforme comptages  | 
| 74   | 0144 Paris 2024            | 
| 75   | 0150 FluxPietons Centaure  | 
| 76   | 0147 Comptages 94          | 
| 77   | 0142 GD4H                  | 
| 78   | 0116 NR II                 | 
| 79   | 0137 Bilan Carbone INSEE   | 
| 80   | 0126 GPS PoC               | 
| 81   | 0135 Skeyes                | 
| 82   | 0121 DRIEA                 | 
| 83   | 0134 Diagnostic CD77       | 
| 84   | 0127 NRHS Tool             | 
| 85   | 0101 MyPlaces              | 
| 86   | 0105 Données Mobiles PACA  | 
| 87   | 0122 Network Rail Datalake | 
| 88   | 0117 Déménagement CD94     | 
| 89   | 0108 CPMS KPI Dashboard    | 
| 90   | 0104 Cartes PL Eiffage     | 
| 91   | 0000 SENSE                 | 
| 92   | AIGP Devillers             | 
| 93   | Choix modal CDVIA          | 
| 94   | EDMOND                     | 
| 95   | 0109 Pietons TdB           | 
| 96   | 0112 IMG Abu Dhabi         | 
| 97   | 0113 Accidentologie Disney | 
| 98   | 0124 Plugin OTO SIG        | 
| 99   | 0125 Enfield MW            | 

# Case studies update

> c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\

1. Create case study images in `images_ODC_case_studies.vsdm` and export icons and images
2. Eventually create new client logo with `c:\Users\dmarin\Dropbox\Pro\OpenDC\01 Templates\Logos\Clients_logos.vsdm` and
   copy logos from `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\images_website\clients\` to
   `c:\Users\dmarin\Dropbox\Pro\info\Git\Project_repositories\opendc_website\open-dc\static\img\clients\`
3. Complete word report: `ODC_Case_studies.docm`
4. Go to `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\md_versions\_md_templates\` to copy template and
   update content with word content
5. Fill `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\website_project_codes.xlsm` to generate `copy`
   script
6. Copy updated files to website folders using
   `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\md_versions\copy_files.bat`

# run local tests

1. run `git bash` (or use pycharm console)
2. `cd cd c:/Users/dmarin/Dropbox/Pro/info/Git/Project_repositories/opendc_website/open-dc` (or `cd open-dc` in pycharm
   console)
3. `hugo server -D`
4. check content
5. When ready:

> `cd ..`
> `git add *`
> `git commit –m “Comments on changes”`
> `git push origin master`
> `cd open-dc`
> `hugo`

6. Empty the bucket content
   in [Google Cloud Platform (GCP)](https://console.cloud.google.com/storage/browser/www.open-dc.com;tab=objects?project=open-dc-website&prefix=&forceOnObjectsSortingFiltering=false)
7. Copy the content of `c:\Users\dmarin\Dropbox\Pro\info\Git\Project_repositories\opendc_website\open-dc\public\` in the
   GCP bucket

*Note:*

To add a video: https://roneo.org/en/hugo-create-a-shortcode-for-local-videos/

````
{{<video autoplay="yes" src="/img/work/video_wXX.mp4" controls="yes">}}<br>
<em>Add video description here...</em>
<br></br>

````

Links ex:
<a href = "https://XXX" target="_blank">XXXX</a>
ex:
<a href = "https://qgis.org/en/site/" target="_blank">QGIS</a>



