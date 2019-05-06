# pretzel-landing-page
Static HTML Content for the landing page of the Pretzel project instance

## Installation notes

(from #dev post Aug 7 - 8)

The current landingPage content is in public.zip in  ~/data/
to install, something like :
```bash
 (cd ~/pretzel/backend/client && unzip -q ~/data/public.zip && \
 mv -i public landingPageContent && \
 sed 's/ src="/ src="landingPageContent\//' < landingPageContent/landingPageContent.html > landingPageContent/index.html)
```

## Additional Multimedia Assets

from  2018-08-01 07:06   public/ 

| MD5sum	    | Bytes	 | Pixels		| File Name |
| ----------- | -----:|:-------------:| ----- |
| a689035	| 6099	| 600x156	| Agriculture Victoria\_logo\_pms 575\_rgb.png |
| 4225622	| 45777	| 733x733	| CSIRO\_Grad\_RGB.png |
| 2f159c5	| 11763	| 659x152	| DEDJTR right black\_rgb.png |
| d0d8128	| 68610	| 1547x792	| GRDCLogoStacked\_RGB.png |
| e88bc99	| 1200	| 94x86	| pretzel-logo.png |

