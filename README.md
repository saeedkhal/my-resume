## my-cv

to convert html file to pdf file 👇️

1. install **wkhtmltopdf**

   ```
   npm install wkhtmltopdf
   ```

   see the installation here [wkhtmltopdf-installation](https://computingforgeeks.com/install-wkhtmltopdf-on-ubuntu-debian-linux/)

2. put this line in terminal

```bash
wkhtmltopdf --enable-local-file-access  -T 0 -B 0 --page-width 210mm --page-height 280mm --margin-left 0 --margin-right 0 cv.html Saeed_Khaled_CV.pdf
```

### to see more options :point_right: [wkhtmltopdf](https://wkhtmltopdf.org/usage/wkhtmltopdf.txt)