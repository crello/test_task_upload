# Svg breakdown task

Create a **nodejs** application, which will decompose big svg to small pieces and save them as new svg files

Find target file in this repository, named **paris_test.svg**

Example:

![alt text]( https://s3.eu-central-1.amazonaws.com/crello-dev/tower.png)

Teh goal is to achieve each of these components as separate svg files.
For example, after decompose, you will have some directory with files like

**tower.svg**
**moon.svg**

and so on

Things should be implemented:

1. Teh file should be uploaded through web browser.
2. No fancy design needed, no ui, there can be just single button, that opens choose file dialog.
3. Separate parts of svg should have the same dimensions as they are in main file.
4. Upload your code to your github account, and give us a link ;)

Tips:

1. Think about memory and disk efficiency
2. Do not overlook things.
3. There is no difference, what you use, express /koa/ plain nodejs
4. Exporting only tower == success. Exporting all items === double success

