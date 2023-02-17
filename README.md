stock_dict = {
  "ICLN": "20.53",
  "AAPL": "145.98",
  "NTDOY": "10.84",
  "ATVI": "76.64",
  "GPRP": "6.18",
  "PTON": "12.65",
  "TSLA": "178.97",
  "FISV": "106.49",
  "VZ": "40.64",
  "GOOG": "100.71",
  "SNAP": "10.68"
}
x = input("Please type your stock symbol:")

z = stock_dict.get(x,"Stock Symbol not found")
print (z)