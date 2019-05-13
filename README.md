1. in the index.html file replace localhost:7101/bali with your server <server>/dv
2. upload the excel 'Demo.xlsx' in this repo
3. in the index.html change the value bitechtest to whatever user you used to upload the excel file. For example: the user could user@company.me. So replace bitechtest with user@company.me
4. login to your Oracle Analytics instance
5. make sure to goto the console->Safe Domains and add in the Embedding section the value: http://localhost:8080
5. run: npm install
6. run: npm start
7. visit http://localhost:8080, and voila! you should see a bar chart.
