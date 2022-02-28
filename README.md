# WM-22

Web Mapping 2022, ESCGIT course project: creating a geoportal ...

# How to do it:

For local development check [this](https://github.com/ayoubft/demo-postgis-nodejs).

1. Go to https://dashboard.heroku.com/apps (create your account)
2. Create new app (give it a name)
3. Add postgres extension to your app in `Resources` tab

   ![Screenshot_20220228_104913](https://user-images.githubusercontent.com/63267601/155961716-14fca10c-00db-4c7b-9570-71b66a3bcb02.png)

4. Choose `Hobby Dev` plan

   ![Screenshot_20220228_105027](https://user-images.githubusercontent.com/63267601/155961951-47187737-b58d-47e3-a081-2e1e320a2fe6.png)

5. Click on your newly created database

   ![Screenshot_20220228_105211](https://user-images.githubusercontent.com/63267601/155962220-dcafe7de-fd4c-4d44-a68a-b263406e0903.png)

6. Go to settings and get you credentials

   ![Screenshot_20220228_105314](https://user-images.githubusercontent.com/63267601/155962383-5a6e702c-7aee-4536-b3dd-4a84bea95205.png)

7. Connect to your database externally (I am using `DBeaver`)

   ![Screenshot_20220228_105903](https://user-images.githubusercontent.com/63267601/155963231-4351d83c-8016-4b7a-b74f-84895897defe.png)

8. Make it **SPATIAL**, and populate it (you can try from `qgis`) or export your tables as `.csv` and import them to heroku database

   ![Screenshot_20220228_110039](https://user-images.githubusercontent.com/63267601/155963433-d2f191ed-f059-4753-a943-2e8cd2377677.png)

9. Link your github repo

   ![Screenshot_20220228_104745](https://user-images.githubusercontent.com/63267601/155961512-2467c310-294c-4697-8a70-6747183fa334.png)

10. Deploy you app from `Deploy` tab using manual deploy

    ![Screenshot_20220228_110513](https://user-images.githubusercontent.com/63267601/155964152-68f9bc5a-4917-4d76-81a8-bd0464bb6535.png)
