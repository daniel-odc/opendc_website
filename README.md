
OpenDC Hugo website update
============================

# Case studies update

> c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\

1. Create case study images in `images_ODC_case_studies.vsdm` and export icons and images
2. Eventually create new client logo with `c:\Users\dmarin\Dropbox\Pro\OpenDC\01 Templates\Logos\Clients_logos.vsdm` and copy logos from `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\images_website\clients\` to `c:\Users\dmarin\Dropbox\Pro\info\Git\Project_repositories\opendc_website\open-dc\static\img\clients\` 
3. Complete word report: `ODC_Case_studies.docm`
4. Go to `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\md_versions\_md_templates\` to copy template and update content with word content
5. Fill `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\website_project_codes.xlsm` to generate `copy` script
6. Copy updated files to website folders using `c:\Users\dmarin\Dropbox\Pro\OpenDC\05 Marketing\Case studies\md_versions\copy_files.bat`


# run local tests

1. run `git bash` (or use pycharm console)
2. `cd cd c:/Users/dmarin/Dropbox/Pro/info/Git/Project_repositories/opendc_website/open-dc` (or `cd open-dc` in pycharm console)
3. `hugo server -D`
4. check content
5. When ready:

> `cd ..`
> `git add *`
> `git commit –m “Comments on changes”`
> `git push origin master`
> `cd open-dc`
> `hugo`

6. Empty the bucket content in [Google Cloud Platform (GCP)](https://console.cloud.google.com/storage/browser/www.open-dc.com;tab=objects?project=open-dc-website&prefix=&forceOnObjectsSortingFiltering=false)
7. Copy the content of `c:\Users\dmarin\Dropbox\Pro\info\Git\Project_repositories\opendc_website\open-dc\public\` in the GCP bucket

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



