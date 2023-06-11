# portfoliEXP 01 - PORTFOLIO
AIM:
To create a portfolio using HTML and CSS

ALGORITHM:
Set up the basic structure of your HTML document.

Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

Add a header section to display your name or the title of your portfolio.

Add images or media to enhance your portfolio. You can use the  tag to display images and embed videos or other media using appropriate HTML tags.

Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

CODE:
HTML CSS CODE:

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Start your development with JohnDoe landing page.">
    <meta name="author" content="Devcrud">
    <title>JohnDoe Landing page | Free Bootstrap 4.3.x landing page</title>
    <!-- font icons -->
    <link rel="stylesheet" href="assets/vendors/themify-icons/css/themify-icons.css">
    <!-- Bootstrap + JohnDoe main styles -->
	<link rel="stylesheet" href="assets/css/johndoe.css">
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="40" id="home">
    <a href="components.html" class="btn btn-primary btn-component" data-spy="affix" data-offset-top="600"><i class="ti-shift-left-alt"></i> Components</a>
    <header class="header">
        <div class="container">
            <ul class="social-icons pt-3">
                <li class="social-item"><a class="social-link text-light" href="#"><i class="ti-facebook" aria-hidden="true"></i></a></li>
                <li class="social-item"><a class="social-link text-light" href="#"><i class="ti-twitter" aria-hidden="true"></i></a></li>
                <li class="social-item"><a class="social-link text-light" href="#"><i class="ti-google" aria-hidden="true"></i></a></li>
                <li class="social-item"><a class="social-link text-light" href="#"><i class="ti-instagram" aria-hidden="true"></i></a></li>
                <li class="social-item"><a class="social-link text-light" href="#"><i class="ti-github" aria-hidden="true"></i></a></li>
            </ul>  
            <div class="header-content">
                <h4 class="header-subtitle" >Hello, I am</h4>
                <h1 class="header-title">shiny sudhakar</h1>
                <h6 class="header-mono" >Im a student</h6>
                <button class="btn btn-primary btn-rounded"><i class="ti-printer pr-2"></i>Print Resume</button>
            </div>
        </div>
    </header>
    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-white" data-spy="affix" data-offset-top="510">
        <div class="container">
            <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse mt-sm-20 navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <a href="#home" class="nav-link">Home</a>
                    </li>
                    <li class="nav-item">
                        <a href="#about" class="nav-link">About</a>
                    </li>
                    <li class="nav-item">
                        <a href="#resume" class="nav-link">Resume</a>
                    </li>
                </ul>
                <ul class="navbar-nav brand">
                    <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFBcVFRUYGBcaHB0cGxsbHCIhHh4iISAbHR0cHiEdICwkHiArIhwgJTYlLC4wMzMzICY5PjkyPSwyMzABCwsLEA4QHRISHjIpIikyMjI0MjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMv/AABEIALcBEwMBIgACEQEDEQH/xAAcAAACAwEBAQEAAAAAAAAAAAAFBgMEBwACAQj/xAA+EAABAwIEBAQDBwMDBAIDAAABAgMRACEEBRIxBkFRYRMicYEykaEUI0KxwdHwB1LhYnLxFVOCkjOiFiRD/8QAGQEAAwEBAQAAAAAAAAAAAAAAAQIDAAQF/8QAIREAAgIDAQEAAwEBAAAAAAAAAAECERIhMUEDIlFxEzL/2gAMAwEAAhEDEQA/AEfD8PuOOJQ4ktk3JMGw9DvT60httIQDYc/b+WrN/wDrjnih0mSLEdQdxR5WcakBSVSOfbsatFolNOgrmTYcSpJEpUIN/wCRSbissKPgV1senI0ew+bBW9rV5zXDeI2VInULi9z2p2iUZbJciKW0BPl1H4jBn5j5CrmNz1CAELCSLhSSdSjItCepMUnrxjgA8pQkxJBMxzjpVvLXGwVqQnz/AITvHUjvSd0UcsVYQwuUqhSi1oTdQTaQneNMzMHaJr5lWDwkqcUgqSSQlJJCRFjb1nepMO5CCVXVYiTGneYHObULRilKcWCZJP1t+1CSBCTYYzBCGodYQANOlSRzSYMxtNqHM58taghCFKUbAJEk+1WstfJc8LTrKzpCZtzknoAJJ9Kb8vydnCo8ka1GVL2J7dk9qTLEvCGYpO8K415XiKCESANKleYD0AIm/UUGcywh9OHUFJdUpKPNG6jANt085BNagrE6JUVX/nKhSc7R9paQkJKlnwyqPN8WwJExKjWjNjT+SW0xkwOAaZZTh0ohtHlkxqWSRCpiJJk+sVQxOMcIPhuaUlWlMhapMdQJSm25Nz2q29iUtFenUqdZ3tI3gz5b6hfmeUUI+yeVQSvWHNCtKDpSYAVJWpJVNh6zflQRNnji7L1LwJ1HU4jzyEkSQeQN5j50j5XgkupkxatFcCgyQ5pFl6SNiNJIMEnr62pb0MBsqb+6WbhYuCei0k39qdCsTH8JoWsD8JgVUQ2pSo+dOHD7zSWytxCXHFqMkgGBMACduveakzbL8OtBcZSG3LkpT8Ko5RsD0ijQLBWSsDxG2m0guLMa1CYG6j7AEx2rVWFNtthAAjYzEnuetZdwW+Ptif8AY5Hy/aabsZjDriYM2/xSylugxhq2NzGMhB8uodP0iqKksOA+CENuCYSLJJv5VJ/aDQbLs1AVpVseZqtn+Cf8RLuFIlQOtJtJF0npO49hWCAMTl2LU54yYBIhadQGgjZO8k3O1DMQjEH4m3PlXpnPHdDja1EOarg/FqBJM/WveEz9fwqNNCm3ZP6WkqKbGEWtUKBT686p4/AONmSCQedGn8xH7RXrF5sFthBANtxckzt600orwT5zb6hcRiVCwmubeJVJO30rWck4UZbZbLiQHCApSvKSVTMbmJFoH+K9pyfBMLOIU22VHafMlIkCRIjVJAJikLCZluXYh5ENNrUD+LZF/wDUq1fMVkmMwaCpxALZuShWrT3ULW78q0V/iVhCZ1T2FAl8UhxURY0aAxUwucFIlMEHfn/OVTLznywNzEetT59w54im1YRs+I4ogoRYRElZmyQDabC4obmnDmKwnhh1v41QFhQUmYPlJGxiTfkDvRUvBHAYBitSBB2H8/ncUoYzMV+OHfMlKbJMR7id6aMFiEMpEmVR/IqtjuIpBEJKTYhXMelGTs0NFL/8m6qWfc11FcoyNosoUpsSQTeZgkkTbpFdUv8AOJXNnZ3woFolp0LUNtQ0n0kW+dKDOBcQ4G4KFEwQrb9janvKsVrWGwSVKMADnTO5w8yf/kUoq7Kgf5otoNfoyLE4ZSD0q1gMyKTBp4zbglDgJYeUkxs5Ck+kgBQ9ZPpSnheC8TrUlwpbgwDOrV3THL1+VFToSXzshziCgrB9vrNBkLCNOkwSJ3586e08BLW3pD6dRIJSUkAidgQSQe96ZWMsw+jwXGG0QI0lI+YPP1o5WzKFLZkgxClGEmVHfpUjOFcaVrSoE84NEs7yBeHfWhpKloICklIJgXsT1EUKcxKhIMyLEGx9DRSTWxHaf4hHh3HaMVrcsSlQHqdJ/IGm/E5wgJm0nf5bUtZBwm7ikeKrUhv8B2Kv9UnZPfc/Wr6uG4TpLpJvGhBV8zqBNucCpSqzq+c2o7KmZ5uVJgHSdyeteMky95x5jEjQptLiCRrGoAKEqI6DfflTPwnwewWkv4oh7XJQiSEBNwlRFioqF4NhItzozicpy1FvAbTP9hUk/wD1UKyaQJNyIMepWhQgLgjypVClAySZ5HoOo3pcWpaXFFaAUmCklUK0wCElIMkDYSmRcUGz7FfZMWfAWVoUhJTrMqRuInnEbmTFDcVmDiwHFNplOy5Vq5mJnqaZInIbl5n9ocaw1tN1OBIMBKRdI5nkPenheKQhsIQhISBAATb5Csw4DEvOOqNwAPnJPpsPrTPm2ZeGlUq5GLkdr/I/Sg+hFzj5LaHG1tpS2VSFpQISSIgwLTuD7UroxiutNvDbYxTi3HBqSPKgG/8AuN/aqHEfD6UvNpat4io08h1UOwEmKbwGNgzI3kt4hpfMqj/2kfrTTjngCbR0A5EneiSeD8J4KSEq1iPvNapkc4nTuNopczR9TS9LgEn4Vcj+x7VJTjJ6Ky+coK2WEPEXmPzo5hc8QhKPEVuTF+lJyHFOGEf4qnm+DcSQoyoGwA+gAFUSdEr2O+FxXinEBLCVNOEnV5QVeUDWJMzIsfcUhN5c4SQQoOCxSRBn06015JkGOWAfK0LGHFwT/wCKZI9DFXcTl+Lw2ITiXWkrbSPMtCgoAgQlShZUAmZiB1tWyiCpFvhngNpTYVjApThuG0qKQgcpKblXW8Daq3F3CGFwrYfbU4kIWgqbUrUlQ1CQCfMFR3ozgOKvFcS2hBWs8kgk/wDHeh39Q/tC20IW0pKFLEqsQI21FJIEnrQUrYcaQTdxTTaDDmtSzqQCogBI0KhBEkC14JmPkPzptIwry1KB8qykCwAA8if/AGAvz9KVW8U4hTTCEh0NjUB/bN4Mbj696YTwy+/hXT8C1QUokQSLkWEJBN46mjzpv4Lpy4qZ8RLoUsASgiLdlTePSnzL+DGPBuVF0p/+STY9QmYjtWVrxq2wptQKSAUlJsQdiK17K80SWkGd0g/SimzSS8LHDGEVh21eLBdJIURsEgwkDtHm96o8e5j/APpOTvqbCQN9WtO3eJqpmWcKXiGmmZWtSCSlHQGxJmBzEkxtRJ7hpThbW67o0K1hCQFSqCAVE9ATYdTc1mKjPsPw5jngCGFJBEgrISPkTq+lAn8udRiRh3UFK9SQU72PMEWII51rmHzctuKaWu6THa9wR2g0C4mw6VY/DPAg6kKST3TcfRRoJt9C0lwPsYoBIAAta0iuqIAch/PlXURADwLhktO4laiFFtKA2TyCivUfXygT+9Wc1zglRGrr60B4awONWUutJCW1CCpw6UqT6fEdpBApmXwy0brfVJ/tAH5zSPpZcBuEzlQUQlUjmKP4XMG3UlCyTz/1D/bAoDjeFnQJZdSuL6VDSfYiRPypYxGZuML0uIWhaRsbSOoOxHcWraZrHNObltxTSl/CYBHPmCfURU3FDrbmE1OEFSCChSTcEkAi3I9KSsFlGNxSlPJSkBd/OqLQAIgE7AbxQvEsYkOLYLagsKhSBeSL2jfrNGjNhHAtYjFuBpq4SLkqISgbAqVv+ZPtR7Gf09dJS4XkOkFJWgpKdSQQVAKk3iRcD2qxws59mZS2r7txZK3NQv0gztAgR6miozpUfGVgjqNxvEiRI6zvTNtiqKRcfzNpTR0r0x5dO0EW0npHSKV3cz8NtxRVqhJFoG5+oG+9Bc6wrzuKWlkatfmUAYSOQKibCw94oDmrLzay27YwDAMgjkR1FTUaYzYdy7ibErabZbbKvDSEgp6DbV0MWqQ5bjXValr0z0MmmLJMO22wgIgeUebqYuT1M19x+apQDp5c6pGKJykwcxww2BLg1qO5UTNB8XlbSHANZDX4kmZHYHpVpedrUd6HZk8FSSdxFOiTZeex4aWfswBCgBA+QgCo8RkmMf8AM5pSOhV5vkAQPnUPDuOS3YC8ST3o8MUpR3rYp7M5uOiTgxBZC2XE6TqJSTsoEDYiva29ePSDcIQT7q8o+k12sLBST79DyINVOGnF/a3EOHzCBq6p5H86l9VUXR0fGWUkmOjyPu4FLeb5QHmyCPMkyn1v+e1M+YLCE6VECaH4YgkjcHnO1cMW07PTaUoUxTy/L9Owgip04gJcAhMpg377kW3io8fm6W3VRdGs363ifSjjHEzak6FpCkmxBAI+Vd72jy+M8DMzyNQv54tKVaro0qBkiDbYiZ+lBsySsYlLeHQpwLTrQkXIvBBJ2APMnnVjOuH8WlrUQ3f8IVKuvSNu9SwKZBT+l7SEYdbv41qIk7hKbBPzk/LpTZiMUlYLbgCkrEKB2INZ/wAD5iG0KYJgglSe4O/vP51PmeZKS5ABJn+e1I08mOqqy7lOSoYdWgbBVlG5UDdJJ6wabGsagQmYrOc7zpxLiVpCtPhp1kCQDKtyNrRQoZy64YQT3PIdyeVWj+RKTSGrirIWn32lAhJWqFkbkQSY72ou3kGECA2kuJgR5XFSOQsSfypAXmLchTji1LRdOkwJ2I2NQL4kcCyUkxYibkU0osWM4jXh2EZa8pesuB2EpWr4gRJ0q9dwR02EXY28+SsSTyrNMQt/GhKYgJM33J2mrD+S4pDRKXAYF07EjnB606g62JKcbpMOuZM9i1OYxlxCpMBBkGEeWypg7HcD1pXxmcuJcbS4lSVNrlSVWItHvvv2olwJxMMOfAcMJJlBJsCd0npPKmfiXKGcc2XEQHUD4h+R6ipXso1ov4VSVISoL3AO4/aurJ05w+0PD1lOm0HlXUwMRm4UzkhhTcmULJH+0gAD2iI9KnezFc70zJWxi0FptI03CQgQB0IAiCKgwn9P1zLuJOn+0JBV7rJj6H1qftjtaoX2c8Un4j71NnLzeKZUFxqAJQrmFATv0OxFF8f/AE9kHwsQQrkHEgj5piPrSJicC808ph0BBG95BB2KTzB/SmqxeD1w/wATYdvDoUtYSQkSOY7V6wQ1leJulTi9VgJ0ggJTflAE+vpSSxk6CS4IISQEg7KUTHuBzFHcxzYpbAUAFgm3Mcu0k7wf+S+jR5YK4oxa3HtSEnyp0mOcEwevWhjWPUrQ2knUpQSOgm3rTBkeSYhxYW5DaCZJXdUdgD7XIog5w5hfFKm1rS7MjXGgnaLAFPremp1om3bPS8Q2w0W2rq5ki6ibFR7/AJW6UrZ4teI8IhMr8yYG8b3mjWIdCZSuEqBII59DJ9aB4hxxamm2klS1LISlG5kcug59huanFV0zdss4XM1obDTnlUkQOh6e9VF4oq3NNOO4XhrSs+I7ErVySf7UdQOp3pFxGtpakKuU86qnQHGy9MXqzlOTuY1ZQghKU/GsiQOgA/ErtI/cKMQtakoQJUohKR1JIAHzNbXw5lbWEw6G5lYutXVR+I+nL0ArZAUBMxvAimUhxl0uFFylSY1DnBG3oaoYbEApBB3v/O9aNmmZIQhUERFYrh8fpcWR8BWoj3JNFSoEoWOTboFV8bmKsM4h9ACvwqHb8J/nWghx3MG1TnEBxtSDzBppJSVE4SlCVhDG8WpduoEnpG1XchWt8KCgUtxFiQfaO16QmXopiyzOQ0kmZEbTXPH5xR2P6yZby/JQ6tSVk6EqKbfi0kgnsLVLneQnDtqcZUohNylRm3Y71BkWdgC8SZkn+4kmY96ZMqW3jlqbVJbABWZiRcaRFxN79JpnLZoxWJf4VHhMphJW6pIKykSb3CRGyRNvc868Z7isQlJUpl0JH+hUflTU0tLaA22kIQNgBAqNWPUOdCxTKGMnUpHiAlLuoqBTyk7dOdQY9zEtpKlhBjnsflWl5zhvGbUWtLb0SCBZfZQ69D1isiKXHSvW4SQSL7Wtt+lP+MvBPyXo+5Tl4OA8Rd1ON6le4kCOwtWfZZg3Hfu2xAB86jZI9ep7UyYbPFJw6GdiAG/T8IMel6IYZkJSEoEAfyfU1OF7DNrRFlfDOHQJcCnVcySQn2Sk/mTUHEGQsoQXGU6FJuUSSlQG8TsQL9KPYZFUc6V5T6RVY30nKnoAZLiy4tLbcAm5J2AG5PanBWFbSJUdZOxMwfYQN+9ZnkuMLLhVuIKT8x+1F15/BsbdOVCc5SY/z+UYodEuNJR5G0JAtpCAAPaguMxziVqewyAUpQS6kQJvYhPXeY6CldebLWrSmSpRgAbknYAU6YLh/FNYVai0VOLTcakz6RN/QUkYlJSHjKMtw3gNnwkK1JCiopmSrzE7dTXUH4RzVP2JgKd0lKNJBMEFJKTIIttXUmQ+JR/pthUtsLfI+8dWRP8ApSYEepkzzt0pvW93rI+HeJfBltxX3ZOoK/tJsZ/0mB6UxrzxRjQoad9QuCO0Vrp7BSa0Oan4rNP6jOBx1pEgOJCjM8lRb5ijrGeJ5n1/h3pJ4uxZdeS6EK8MJCQvSdKjJMAxBpld7A6S0TYbMm22EN2lIg9zz96GNLcdfabOoBTiQCoRMkCfYbUVybLEg+IoeY3vy/zVjPMwQW1JT8QIKCN0qSbEe9UxJOfg6YpYabt8ShZPQUsKWZn9YoL/ANceUhK1pJtGobdL1CM31lKQFKUTYJBJPYAXJo5UhcbZNxbiIW0sHzKR5u+mNJ+Rj2FHuGlNYZnxCoFxxIKlgSUpJnQnoNpPM+ggdgcixilKccwqikiAFCFR2vbrcUIVhiHkMJWpGtcKSfwgXNiN4+tDux+D7j+I2kNlQMq2A5knYCrOX8FYdf3z33ri4JEnQP8ASkDeOppXxeTshAgGRBCySVT1F/pEVeyzjLw5acJlNhexHUH+H1itJNIEZJsPYngTDSFNIDa0qC0KBMggyJEwRIoRxDm+Iwh+9bOkmEuJuhXbqk9j9aLNcTIUJ1FQ5Tf2k7+9QZxnDLuHdQ5JSpB32kXkdCDHvWQRFxOaOYgkXSg/EOv7VLhcobcSAsEA7RYevqaGYN4Bs6jCopwXiGwAARAAj5f4pkJJNC3juHVoP3a9SeU0IxKHG/KoETz69Yp1XmCQLkR0pfzrMUqbKY5iO0H9pHvWaAmCG0daPZHkQfhbkhGyQN1fsKWrq2BPoKb8gzkJeaSfKJIuI/CqPrFK5aHUdjYOBGdFkNhUdTPzFDeGsKcHiH2lhSSQhSdXMef4TsoUaTnZ1b+9eOIcSlzDqUD942NaFc5FyPQi3/FQU2+lsK4FjiAb1EszSflWfBQEnennh3CeKnxF2QT5R/dHP0/OnFKiDBmaDZpkTeJ1LbhDqFG4sFcyD3k71pSGEAQEpjpApW4myZYQXMI4GjOpwASlST8Skg/Csb9De1GLoWWzLU4dpxSwsKbdCobWZ0kpsU9JChRzKluqOgsO6huUtqUk9wQIonhca22QQgKLYhClgWmZVPWee+/Wr73ELmxXEdTTt+C4elc5diSCUsr9xB+RM0u5tiVtgpdSpBvZYIPrBF6dMPmo8PVIJ9b1Icc2+jw3UpcRIIChcEbEHke4rKXgH8/THUZc8E61tOIQb61IUE37kRXBpIuYraU4lCCWzCkkWnmDyPLtWQ8W4VLOKcbQPuzC0idgoTpHYGQO0UrRRMP8AZLrc+1KT5UmG55nYq/Sa1FLlqWMgzBDjaFIgIgQBsAOXbpRPE41IupQtc/80W6Fqxbzvh1px9xekeYg/QV1U8RmLrqi42qEKPltuBafeJ966tTDaK3DHBbbwHilRsFL08p+FAPsZPauzngwsGcO4oJVslRPe3W8Vf4UzkMtuNqJWoOKGwunSgJnvv8AWpM54kbKAFJuVBIuYAJCTJEQIv8AKh0OhVy/JluJC3FkzfRP0Mc6fcPwqXWEoWstpMEJCQTa4mdqoowOFTimNLhTKzKAfKogKVBB6kdp7zTFnedttgyqABKjQ9MZVneKcYdcw7gTKTAKdiPwkeo/WghxQJv/AM0+YDLG8c45iXgSmR5ZIMbJTI2sCT/mjjD7bUpbaQhI5AAe560ydgcTO8rW6cO6EpToSQfNuTvCbbwOfWn7hzK2sG2FEAvKEuL53vpT0SNrb71Rz/NEkJ1JCQvyT3AKkmfY/OveRNP41Osjw0AwVrFiRY6B+P8ALvQlwaFWG05wZ3g/SlnjJlCltYkCHArSpY5gghOo7EgwPen3AZY00PKmVc1qur25D2+tEDcGbjaDsfbnSLQzdqjEHM2dT5CncwLWvaaIuZVhl+dwkqIEq1Ee4AMRR3jnImAkqbltweaATp9IOw9IpEaxqiAJ2tVoyyOeUceDbwjlWFQHS6fEKVQkKJgJ0ghUA73N+1COKcqS2+Aha/CcGtCZPlIMKTfcAwfftVBnGKbcSQVQ4AISJkyfLHOZiO9EeJ8FjPu33GlIaSNKT5fLJHxJBlI23paqRRtOGugJ7Lj+En3qFSnEbkwOdEW8ak7mD6V2LxKAgkGbRVGkc6lLjPOVNOvr8NpJUqJPQDqSNhR/F8Ju+ARpQVjzC95ja8DtTlwZlScNhEAR4iwFuHuRITPYGPbvUmKxALgRy3PtU8joUUL3C2RBptKnUy6fw8kfLdXU/wDJIZ/w+2+AR5XE3Ck7229aJhHMmBvt+1U8c64Ey0AYm1xPP5e1Y1CTmLb7HmdEo5LTt2npVdWZOOoKEzBEE034vHhbBDiNJI0qSrkf161CcGhLZ0JtFDBWbJmf4TCuF1DSSQVrSgdtRAn2ma/QuDCW0JQkQlKQkegED8qx3IoOOa7FSvkkgfnWsIc2ilnphjtBMOVG4apLxEH3qN/FgJJJ2F6yMCMJmgMpN4kfKRQPP8jbcJcZV4bnNIshXaPwnuKUWM5VJVJGoz8zNF8uzIuuJbSSFHmVWA5k/wA6UEqHtM85LhC4uEpcUoWUJA08vMYge5pxZ4f284T1AOofmKtB9vDtkIAGxJ5k/wBx6mhrmb64hduxuP8Anen2zJUe15CoLKziCr/w26AealfiDht0vLeWErbgBKkGYiAdQNxck8x3owc0Vr0TJ32+polg8XqCr2jbpEWve83H+K1tbM4qSozrxHcMD4SiUG5SeR6iosNjH8YvQVEI2UBz7Uw8QpQ3DgB8NalJNvhWJlJ6AwSPQ7WmhwUwXHnG206rhU8kg9Typu7I8eI1YXCJShKY2EV1HBw85/3G/r+1dQyDRkmLxJPlRYD69z3NRNNuOJXpbW4APNpSpUesC1MbeQMj4lLJO5kAfKKaMqx4w7aGkIlCREgwSTcqNrqO5rN0BLexb4Hy1tx9Cn1eIkNqUgEmQsFAnqYCrHr6Uf4p4P8AHSVs4hZIuG1xpMcpAB+c0oNYHFIxocbCQnWoplYCdKiZSTyt9QKO4zM3kKOlLkgxAEg+4t7zWdWFaQDyDPAxracECbzulSZBB/m4phw2OQ+dDRC1kSQOQ6n+0dzSRmDTpcUtxspUtRMdyYArS8qwreEbS02kTAU4vmtV9z06DpQ4MnYvZjwtiHXWUOKb8LWnUErOoDnHlA+GRY860LDs7AQEJACUgQEgWAHtQHEYo+I0ubFxAPuYn600QAKVsaqPsVXxWI0J1TH5nsKG5rnzbBGsyeQ+kevbelji1OYvt628O4lojzEEa9PQIB1AR2ntQ7w39BGOxwxDzrilfdDyoTyMbn3NJ2LWA4rTAE7DaiWAUXFJabIBPM7AdTXvMsubaACPOY8yyfiPboKtpKkRVttsKcA6XMUFLAPhplPqoxPyB+daHn2PbLTiVQUlJBB9KybIMyGGU6TYrACSO0z6b0wZL4mNcGoHwUmVE/jPT/b+3sVf7GWtC/lfC+LfGpCIRyUs6QR12J+lFk/0+xHN1qekmJtaSN79K05Co0pSBCelhMfz6V5Q6Fk7FItvMkdpi37HlS5DYiNlmcPsuttuKlAAQ4mBANk6kmAYkA/+RrxmOYkYxSeSkQPnNWOMsIbONmFDeem8GLzsR70hrxDjiwo7oMT6UyA2aMM68JI1XJ/n61bw2aod+FQCh+GlRplRSBM7lM+x/WrCEBHmJAIFuVNQuR5ztZexLWHQSfxKjp0p5w2F0JjSdgP8d7T6fOkLg18LxDjquat4mEjb0vTljc10WJ5zqAJ53tN7RERSMwJzTApaxDeIiCDpUdpB8snlvFN2EeBEz3rOeKc2+4LZXKzAt/LSBIHfaiXCWcFaACbxFCUdDxkNGY4qCKB8TZkpOFc0zqUnQPVVp9gSfavmaYqVb9KXcfmIU4lvdKd/Xl8v1oxWjNih4hFjIPQ05cDI0y4oSVQB1gXt6muzvKEONFwABQEireRJQltKZiBP8+lZ8Gh0s5w+pa1SvSNoPO1t+UGoWE8jKTG4tPpRUoaIBJBiwIE/pVXENykkEzYR7/tRQWUmBOtUgz8xfrVzDOwnymQTc2/lqrtEJJsSfb1tbrRJ9Eq1CJNyDy2+uwmiYr8SYMLYKdcBam7C8HUCVJnawVI6+ppl4QwjbbeltASkfMnqo8yaUlu+LiEoFwgbfQfrWgZPh9CQKDVIRu2Eor7XyRXUlAsxlWM7nn+levtagAeXMT/DQ0k+9fAu38+tWojYZ+2wLKnn3r0rHkRJn0PXa4oNi3kavu0kAgEgnY84jlUIevaslZm6GHx0rsq9+mxFwenSrCc3/wC4RtE8p5H50tDFe1elS6nwxufKm/M7el4pZJDxkw3nOaANEpUAdxHI8jQ1zj95SAkiCOm1MmTf09a0g4t1Tiv+2gwgdifiV62os/8A0+wDiClLam1clJcUSP8A2JB9xSNIpbFb+nyFYrErxD3m8IQgHYKPP1A/OtdbckUh8KZIrBOPMqOoHStK4iR8J9CIFqak4mP1vWaMZr/UjL/suI8VtIS2/dccnE3JH+4GfXV1oFkGWu4xZQghLafiWq6UzyAHxK7VpXFuCbxTXhrsdUpP9pCSJ+tCeGMvVhWktqWid1aZIk73IFbLQcShi/6aAplGIVrj8SRp9IFx86tcPOpYaS0qA4klKx0N55c9x2+VMqMenbV70kcYYV0KViGkqBSQFR5goW80DaJ3tzrAqhrazBGkwbgwZPzm3Peec968LxyAAbW+neOt/lWWf9beiDEH+etRvZm8qwPxbwm/bvRxNkNme5hqUG2zqU4THabflNQYjK0tNwBKudqDZRgnUOJdcAi+6vNfpFMWNzBK5TpM+tPGLJynH9i2xm3hkBYMJsCDy7j9a+YzFOOzpBgjpyoph8E2tshcBZJJnfnEdREVXZzVDKPCWiSmwUOY5VnaMqYHyvMVYdZgb/OrS85WoyAT1v8Ar7n51UaIcWpREDkKuDCiOg5dT+woJWCUkgVi3VuKlRkn+WorgVv4calNK0mvWQYdK8TfZImtMbS24gpgHsa1BTMtxmeuLNgR3Ne8t8xk7005rwkmSWxY0s4nLnGDIBUnpzH71qNYyYk6mz5rRty7j/NCMixwCwhR6pM9fw/OhozckRJvyqgHFJXqggc6DQ6lTNKHxSLDpN59B/NqlccCROmFTBPbsPzO/wCVBE4wuIGmCVRJ/nv+xrwvEkGJNu/ptNBMsEUkKI/P358x9KpZpmIaC1GCRsO9V3cQVrDTKVLcWYShNyffoBuTAA3NNmX/ANN0uaV41xSjv4TZhA/3L+JR7jT789YrYrf06X4j7hWZV8R/xWuoMCBVHBcKYFogtsJQoCNQUrV7nVJ968Z34jLZcbCnG03WgfGBzUn+6Om/rtQbsmtF3xe9dSUjjXCED70+9dWph0IJXb3/AGr4qwjvyr74Z/avgbVViB5UrqarrVUjqCDVYmsAkC6v5KSp1Av8QPyMn8qFTTBwrhiXNcWA3pWUijT8IvqelE29qDYSigcpKKAbNc+bYxAbcISFpGlR6yZE9bj1qvjnXtWtpxvwoklW4686UuKicTiktqIUGh59O0q2TfoIn1oBjsW4FKYbcUW4gpn6Sb7d6KWgXsYG+J/GxJSD5AmEn+4z5lfQR6d6ZmlSJ3nrWTNtrS5qFimDTexnyAkSog7QJn0tzoqKA5tDX4KbyYPI/wCK9IdUm0ehH03qhgGMS6kKhLSDzcuvsdA235kGveO4bxK7/aQsc2wnw/bVqM//AFoOg5NiZnb7Rx0iAgRrgW1kGSY25e81SzLENocT4ageduXStEy7LUadBbSANxH8mrGN4ZYdbKS2lI5EAAjvIrXTs1WqM0Rj1VKMwv7VUzbL1Yd0tKvF0nqOvrVUOVVTOaXzC5x4VOr26/OhmJw51SVap2JP0qcZY+Wy6GXS1E6wg6Y6z077UR4ZyYYjzuE+Gk2A3VG9+n7UJyVbGhBp6A2HbcTJShSkmxKUkj6CvLuKWLGfcRWlu4pCBoQkBIsBFoqi8lLkhSUlJ6j+XqeRZwXol5FiNClrJ6DvvTV/1jwyLmPp6d6WM1wSsM4QB92v4Sex2Pf+cqmyzAu4k6WwNI3UqyR2ncnsKZCsbcHxKLAi/P8Agr3jMY04k6ooSeDXAJDyJ6aSB85P5Uu5q28wrQ4kgnY7pP8AtP6b0dA2XslwCVuuKERqIFjYczb0j3o7jcqRpJM80wExcc/4I9qGZFKEDeTOwk9TPQfnNFHMQUpPqBJJ1bbDexCj86wBLeW40YSSE7xyqJeYOHmB6Cr+cFJmJ99/2qLC5A+tGsJ0piQTv6xStbKRk6NT/pdk6WsN9pUJdfk6juEAnSB0BjUesjpTqSTQ/KcOG2Wm0/ChtCR7JAq/MVMYixGK0DyNqWZAhI5nubcutRYPFuuEhbOlI5lQ+nX1r27itM1XTjtU3mLGOXb1pkhWzP8AO/6ZuLxDi2FpQ2pUpSRtN1D01THaK+Vo/wBpHWupgWYVqqNaq9LXUC10wlHKX1qDV1r4tdfW0E7UGwpHKXFuZp04ViN4gUlpwalHvUreMcaslXzoDGu4Z9KYKiJHPvsao4/M3XJbYuvbVHlT3PU9qC8OZY9iILzhCd9KbfM7/WtDwmBbbSAhIAHQRQY5lWZ5PicKgahq1qAW4ORUd1A7TO9MuQ5az4egoTJuTAk+pO9N+PaQ42ptQkKBBB71lrXEaWwUKnW2ooPcpJTI9Yop2BqgVxAhOGxTjafMkgEcyJm3emrhTh/wtLrqfvFiUyJ0dugPU9beorh3L/teKOIc+FJsD1gkc+Qv6kdKfGlJI8pBEWUNjcyNze319aWT8NFek+sJCiLT8U87RJ9h8qlDiSkCTCoAH6j2oaXFEqCvLsAQQJ2n0sOdekrNtM2mPbl2BvagkZl7FISAF9LETy5etRHFWrw6tK0KGm8R36/nSRj+I0oQTN+QrVsZPRT/AKguJW41HxAKn0tQ3hPKQ9iAF3bQCtQ6xsD2594jnVB1DzhU8pCim1zsByibkd6eP6fYVJbcdO6zpH+1I/dR+VPxCrchky7MS45KSPDR5VJgzJuNthHt9KoYnKRhHdTSSGHD5QNkKJJUgjkDuO0jlc+ylKQAm2wgj8p+deOJlgYN5BNy2ojqCBKVeoIB9qUdi4vCIFyqFXnmkn37V6ThEJE6tXt/JpXwOelxAkecDbe/UVJh84cBhW3OaGLFyRHxavU2lFtSljT25frRTDPIZbS2mwA955k9zv70u5hh3HIxCrJHwD0O/vFfHMVqEg71SKJzf6GJOcmd6mU42+2W3RIN+4PIg9aUUumpm8UU7U2idtFvEYrwSpuTKe9j0V7iLcpofi8xKovtP59d6iztzxHEKFzoAPzVH50KgkhPWlbodRTGThjLDi3xP/xogmeZHKtRdwaUt6YAH8/zQrg3LUtMjkSJPef59aNY5waVfLlP1pW/B4ot5JiQtlBHIaT6pOk/lNWnXf8ANJnD2ZBvEO4dVgslbc8zsoe9j7GmRzECLUgzPOMbLqSArTPOCD/Pzqv5WkpbRtzNpJ6nvUT2JmqnjQaohGEvtB6K+Rrqo/au9dTGMcRqVMXiJ99q9hpR5GmbJ8uH2VKyLrUpYHb4U/kT/wCVE2MsSLxvv1qaYziJ7WXLIkiieGys2tPamtjBJI2t6XqHEvtspJUdMeneBWtmxQMzLCaEQLE9uXrVHJcnL7mr/wDmjn1NV8ZmbmMdS02ClKjBPOBue1aXkmWpaQlCRYCj5s2rL2X4cIQB2q6V1GG+8dq8qbPU0tjFLNsaGkKUdgJP51kZIVqUR5lEq9ySfzNOfHuM0N+HN1mPYXP5R70i4Z7U80nlrTPsZ/SnjpCS2zTsmwoaaQgbxaBueZ9bmrIgKOm0TAG1ySLbQTX1lXlSTY2/LlG/pULg1J3mbGCYmbGen+KT0J6Xa6iI6842An5mq6XEiQkzogwkbHkNrza3pUrrmiRoKzq2TtIAkA8haY9ahQhMlYAIVGqLzEAJv0j2ogJwsquJTa6JMjbmTv8AuKy7DthDi3Fp1kKVpBukQfiPp0rSmVKQHNawbgotcDfSq14A5dazDDlx2yQojoNr9Tt86KGNNwGEGJwyVLSlLqk3I2jlb0i3c0CKHsttpC2pmU9/XY3qthX8cgeQCIsAoSB25R2oVmPETqwULImdovb8qKM2hqXx80ojU2ox15e1ceLmXpbUSAoESoW2IhXzpAawLjg8SwB+vLkO1XMRkDiGy7qSpCCNekmUgmAYIuJ50cX0T/RXVkLeAWgqUlQABIT3AJANTYLxMQ+htxUJJ80c0i5v9KhfxE7bcq9Ze24pxtQCwgq0KWAYGrym+3Oi0kJGTfTTTlf2lvQ3pQ0PKVkWHLyjmfp3oTjOCcO2ghDzpX1OnTP+3Tt70XezZKQltvypQIAHbaheMzPUQkeZSjASLknoAKWylIz1/WhxTZEqSYMfQ/KreGwDy9kEDvRH7C4jEEvtltSzqAVFwLCCCQdutOeD0EAiJHSjYjF3A5FYaqp5zk3hLS6BKU/FHTr7fvTwtxI7VWfcSpMHnWs1UTZXmILYSmxj+CvKn1LSZBBG3uYpNwAWjE+AgmVKGi/LnPYAH2FavgcI0lIkBaouoj5+npSS0ysXoz3OMIQNaCdSFSlQ3BG0e4rkcXAp0uDw3NiY8pO09vT60Sz7OGCtSWm/KkwpSVQCZvA297UmcQqblI7kn26n3raZrGfDZ2lRhTiPnv7Tb61K7nLKd3E/OTSjlim3SoEeYCwA39BRfE5IqNSW1bX8p/LegmYtK4ja5FR9v811BFIQLEGRvXUbYNBDh/iRpIQy4gpKUhAULpOkRtveJolm2bMlFlKTGxAM11dQGQBx/Fh+FpMdCaCuqW6da1lR5T/LV1dTREkN39PcsB1PEbnSPQb/AF/KtGbTHtXV1CQ0eHxS6qOOwD/Odfa6gMjLONFqcdKgfKjyx8pP5D2oPkjZDzSuWtP511dTE2au26ZgXUmSRta/PmRNSPqFzuQY/b+d66uoBRULypBBvsZ9OW8Xj2rxaL6gYkgEbbn1+fKurqwQdnTuht1yYJnYdhpm+8EbelUMkwgKBfeLHYbxt6V1dWfALqLOOdAUlNyQIsY3tO3UDnUuWoYWSh5tK0L5keZJ2BBj09K6upIjS6ecPkCG3HMKpRhI1tK/0qM6VRexB+dV8S9oSWQNWoFC56Ry9r19rq6Y/wDJzTSUhGYw6yUp/uMTPzNNnESlBhgBsNgi0KkiCIFusXrq6kQ7AP2x8qSm2pRgGaespQ3hEhQ87ih5nCL9wn+1O1gPc11dQ9HiT528HsK5q+JKStKuYUAT9dvQ0pZRnZAhXSurqyBMLKx+o2J2qBnGqCq+11OSKuX4sfb21HosD3Sael4tQbWqdkqP611dUPodEOGdh0gX5zNfMsy9WMeSwIH4lE/hHUdTyrq6hH0Z+Gn5Rw0zhxpbSAo7rN1GOZPzsLdqLeAE3PvvXV1KP4RHLkK82gX7Curq6mFP/9k=" alt="" class="brand-img">
                    <li class="brand-txt">
                        <h5 class="brand-title">John Doe</h5>
                        <div class="brand-subtitle">Web Designer | Developer</div>
                    </li>
                </ul>
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a href="#portfolio" class="nav-link">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a href="#blog" class="nav-link">Blog</a>
                    </li>
                    <li class="nav-item last-item">
                        <a href="#contact" class="nav-link">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container-fluid">
        <div id="about" class="row about-section">
            <div class="col-lg-4 about-card">
                <h3 class="font-weight-light">Who am I ?</h3>
                <span class="line mb-5"></span>
                <h5 class="mb-3">A Web Designer / Developer Located In Our Lovely Earth</h5>
                <p class="mt-20"> A Creative, hard - working, self motivated, diligent, team spirited and positive person who wants to explore, learn, create and develop new ideas in the IT sector. Quick learner & highly energetic learner with a clear interest for learning and productively applying new knowledge resourcefully.</p>
                <button class="btn btn-outline-danger"><i class="icon-down-circled2 "></i>Download My CV</button>
            </div>
            <div class="col-lg-4 about-card">
                <h3 class="font-weight-light">Personal Info</h3>
                <span class="line mb-5"></span>
                <ul class="mt40 info list-unstyled">
                    <li><span>Birthdate</span> : 16/07/2003</li>
                    <li><span>Email</span> : shinecandy65@gmail.com</li>
                    <li><span>Phone</span> : 9345364542</li>
                    <li><span>Skype</span> : shiny sudhakar </li>
                    <li><span>Address</span> :  12345 anna nagar , chennai 602024</li>
                </ul>
                <ul class="social-icons pt-3">
                    <li class="social-item"><a class="social-link" href="#"><i class="ti-facebook" aria-hidden="true"></i></a></li>
                    <li class="social-item"><a class="social-link" href="#"><i class="ti-twitter" aria-hidden="true"></i></a></li>
                    <li class="social-item"><a class="social-link" href="#"><i class="ti-google" aria-hidden="true"></i></a></li>
                    <li class="social-item"><a class="social-link" href="#"><i class="ti-instagram" aria-hidden="true"></i></a></li>
                    <li class="social-item"><a class="social-link" href="#"><i class="ti-github" aria-hidden="true"></i></a></li>
                </ul>  
            </div>
            <div class="col-lg-4 about-card">
                <h3 class="font-weight-light">My Expertise</h3>
                <span class="line mb-5"></span>
                <div class="row">
                    <div class="col-1 text-danger pt-1"><i class="ti-widget icon-lg"></i></div>
                    <div class="col-10 ml-auto mr-3">
                        <h6>UX Design</h6>
                        <p class="subtitle"> i can design basic ux designs</p>
                        <hr>
                    </div>
                </div>
                <div class="row">
                    <div class="col-1 text-danger pt-1"><i class="ti-paint-bucket icon-lg"></i></div>
                    <div class="col-10 ml-auto mr-3">
                        <h6>Web Development</h6>
                        <p class="subtitle">I do basic web developments</p>
                        <hr>
                    </div>
                </div>
                <div class="row">
                    <div class="col-1 text-danger pt-1"><i class="ti-stats-up icon-lg"></i></div>
                    <div class="col-10 ml-auto mr-3">
                        <h6>Marketing</h6>
                        <p class="subtitle">i can do marketing</p>
                        <hr>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!--Resume Section-->
    <section class="section" id="resume">
        <div class="container">
            <h2 class="mb-5"><span class="text-danger">My</span> Resume</h2>
            <div class="row">
                <div class="col-md-6 col-lg-4">
                    <div class="card">
                       <div class="card-header">
                            <div class="mt-2">
                                <h4>Certification</h4>
                                <span class="line"></span>  
                            </div>
                        </div>
                        <div class="card-body">
                            <h6 class="title text-danger">2017 - Present</h6>
                            <P>Udemy</P>
                            <P class="subtitle">Amazon web Services (Dec 2022 - Jan 2023)</P>
                            <hr>
                            <h6 class="title text-danger">2016 - 2017</h6>
                            <P>skillvertex</P>
                            <P class="subtitle">Cloud computing (5 Sep 2022 - 5 oct 2022)</P>
                            <hr>
                            <h6 class="title text-danger">2015 - 2016</h6>
                            <P>Sololearn</P>
                            <P class="subtitle">HTML & JavaScript (25 Sep 2021 - 20 Nov 2021)</P>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card">
                       <div class="card-header">
                            <div class="mt-2">
                                <h4>Education</h4>
                                <span class="line"></span>  
                            </div>
                        </div>
                        <div class="card-body">
                            <h6 class="title text-danger">(2020-2024) - Present</h6>
                            <P>B.Tech Information technology</P>.</P>
                            <hr>
                            <P class="subtitle"></P>
                            <h6 class="title text-danger">2018 - 2020</h6>
                            <P>Hugh school Degree</P>
                            <P class="subtitle">Csi jessie Mosses (Mat,physics ,chem, Bio)</P>
                            <hr>
                            <h6 class="title text-danger">2018</h6>
                            <P>SSLC</P>
                            <P class="subtitle">St patricks school(computer science,Mat,physics ,chem, Bio)</P>
                            
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="card">
                       <div class="card-header">
                            <div class="pull-left">
                                <h4 class="mt-2">Skills</h4>
                                <span class="line"></span>  
                            </div>
                        </div>
                        <div class="card-body pb-2">
                           <h6>html&amp; CSS</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 97%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>JavaScript</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 85%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>c </h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 80%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>SQL</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 90%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>Java</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 90%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 90%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                       <div class="card-header">
                            <div class="pull-left">
                                <h4 class="mt-2">Languages</h4>
                                <span class="line"></span>  
                            </div>
                        </div>
                        <div class="card-body pb-2">
                           <h6>English</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 80%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>tamil</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 45%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <h6>malayalam</h6>
                            <div class="progress mb-3">
                                <div class="progress-bar bg-danger" role="progressbar" style="width: 67%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

 

   

</body>
</html>


OUTPUT:


RESULT:
Thus, a Portfolio is created using HTML and CSS.
