# ReadMe.md
Official Account For [IPQuery](https://ipquery.io)

🌍 **Translations**:  
[🇺🇸 English](https://github.com/ipqwery/ipqwery/blob/main/README.md)
[🇪🇸 Español](https://github.com/ipqwery/ipqwery/blob/main/README_ES.md)
[🇨🇳 中文](https://github.com/ipqwery/ipqwery/blob/main/README_ZH.md)
[🇫🇷 Français](https://github.com/ipqwery/ipqwery/blob/main/README_FR.md)
[🇩🇪 Deutsch](https://github.com/ipqwery/ipqwery/blob/main/README_DE.md)
[🇷🇺 Русский](https://github.com/ipqwery/ipqwery/blob/main/README_RU.md)
[🇮🇳 हिंदी](https://github.com/ipqwery/ipqwery/blob/main/README_HI.md)  

---

## Stats
- [X] 📈 35.2 Billion requests processed.
- [X] 🌎 A Feature Rich Free Geolocation/IP API
- [X] 🖥️ Proxy/VPN/Fraud Detection
- [X] 🕒 ~8ms Response Time

## Get Featured
Have you integrated the IPQuery API into your tool? Or did you make something cool that you'd like to share? Send us an email: contact@ipquery.io

## Found a Bug
Open an issue [here](https://github.com/ipqwery/Bugs) or contact us support@ipquery.io

```javascript
fetch("https://api.ipquery.io/?format=json").then(
      data=>console.log(data)
).catch(
     err => console.log(err)
);

```
```json
{
  "ip": "103.126.161.54",
  "isp": {
    "asn": "AS135959",
    "org": "Onebim Vietnam Limited Company",
    "isp": "Onebim Vietnam Limited Company"
  },
  "location": {
    "country": "Vietnam",
    "country_code": "VN",
    "city": "Quận Mười",
    "state": "Ho Chi Minh",
    "zipcode": "",
    "latitude": 10.7888515998133,
    "longitude": 106.659162009128,
    "timezone": "Asia/Ho_Chi_Minh",
    "localtime": "2025-05-03T15:27:59"
  },
  "risk": {
    "is_mobile": false,
    "is_vpn": false,
    "is_tor": true,
    "is_proxy": false,
    "is_datacenter": false,
    "risk_score": 50
  }
}
```
