# fno-dashboard-data

Yeh repo **STOCK SUPERVISION FnO Desk** app ke liye Bhav Copy data store karta hai.

- `data/` folder me daily NSE F&O / NSE Cash / BSE Cash / MCX Bhav Copy files rehti hain.
- `index.json` batata hai ki kaun kaun si files available hain — app yehi file check karti hai.

Naya Bhav Copy daalne ke liye **Data_Uploader.html** (owner tools) use karo — woh khud
`data/` me file daal ke `index.json` update kar dega. Isko hath se edit karne ki zaroorat
nahi hai.

Software updates (naya .exe version) is repo ke **Releases** section me jaate hain, is
`data/` folder me nahi.
