# Bootsrap1-Pemrograman-web
Putri Yanti_ Informatika-A_231730022

## Here is the list that is needed
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/accordion/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```
## Head Syntax
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>company profile</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
      crossorigin="anonymous"
    />
```
## Navbar Syntax -> Navigasi 
```
<nav
      class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top"
    >
      <div class="container">
        <a class="navbar-brand" href="#container-fluid benner">Welcome To Animasi Doraemon</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse text-right" id="navbarText">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#layanan">Layanan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Karakter Doraemon">Karakter Doraemon</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Tentang">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#About Us">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Kontak Kami ">Kontak Kami</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
```
## Body -> Benner Syntax
```
<div class="container-fluid banner">
      <div class="container text-center">
        <h4 class="display-6">Selamat Datang di Website Animasi<span></span></h4>

        <h3 class="display-1"> Hai...<span></span></h3>
        <p>Salam Hangat Dari Kami & Semoga Sehat Selalu</p>
        <a href="#layanan">
          <button type="button" class="btn btn-danger btn-lg">
            Cek Layanan
          </button>
        </a>
      </div>
    </div>
```
## Body -> Layanan Syntax
```
<div class="container-fluid layanan pt-5 pb-5">
      <div class="container text-center">
        <h2 class="display-3" id="layanan">Layanan</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate,
          doloribus.
        </p>
        <div class="row pt-4">
          <div class="col-md-4">
            <span class="lingkaran"><i class="fa-solid fa-heart fa-5x"></i></span>
            <h3 class="mt-3">Pesan Moral dari kisah doraemon</h3>
            <p>
              kasih sayang, tolong menolong, Kerja keras, kontrol diri, Kepedulian. Digambarkan saat Ibu Nobita merasa 
              senang karena Nobita telah kembali, hilanglah rasa khawatir seorang ibu yang sekian lama anaknya entah dimana.
          </div>

          <div class="col-md-4">
            <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
            <h3 class="mt-3">sejarah Doraemon</h3>
            <p>
              Lahirnya Doraemon bermula ketika seorang komikus, Hiroshi Fujimoto (Fujiko F. Fujio) 
              bertekad untuk membuat serial komik setrip baru di sejumlah majalah sebagai pengganti komik setrip karyanya                 sebelumnya, Denka Dari Planet Ume (Umeboshi Denka) pada tahun 1969.
            </p>
          </div>

          <div class="col-md-4">
            <span class="lingkaran"
              ><i class="fas fa-i-cursor fa-5x"></i></span>
            <h3 class="mt-3"> tokoh utama</h3>
            <p>
              Doraemon (ドラえもん) , Nobita Nobi (野比のび太) , Suneo Honekawa (骨川スネ夫)
              Takeshi "Giant" Gouda (剛田武、ジャイアン; nama panggilan: Jaiyen)

            </p>
          </div>
        </div>
      </div>
    </div>
```
## Body -> Portofolio Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="Karakter Doraemon">Karakter Doraemon</h2>
        <p>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Id, delectus tempore 
           consequuntur porro mollitia maxime amet ab, quod autem earum eum doloremque ut officia 
           saepe eius! Aut totam et facilis!
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4">
            <div class="card crop-img">
      <imgsrc="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxASEhUSEBIWFRUVFRcVFRcWFhgXFRUVFRUWFhUVFRYYHSggGBolHRUVITEhJSorLi4vFx8zODMtNygtLisBCgoKDg0OGxAQGislHyYrLy81MC0vLS8tKy0tLS0tLS0tLS0vLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAOEA4QMBIgACEQEDEQH/xAAcAAAABwEBAAAAAAAAAAAAAAAAAQIDBAUGBwj/xABTEAACAQIDAggGDQkFBwUBAAABAgMAEQQSIQUxBhMiQVFhcYEyUpGSodEHFBUjQlNygpOxssHSMzRDYnOis+HwFiRjg8JEVGR0o7TTJVXD4vEX/8QAGgEAAgMBAQAAAAAAAAAAAAAAAAECAwQFBv/EAC8RAAICAQMDAgUCBwEAAAAAAAABAhEDBBIhEzFRIkEUMjNhgXGxFSM0kaHR8AX/2gAMAwEAAhEDEQA/AM9szbBLNljZyTmVB4SjS9zutfXvqLsUrJPKW1zKAA2hC7mWwPWB3Ve8F9mRrGJI2ZmdOX0BhvFrXFiCKfwOzIirsgDEhrDpIJBBNuc6VyZSinKkJJlfs6OBHkyleRb4V8q219IPlqYdo5QxkU5AVylRfMGNhz9Y6KoouD2KcnKlgN1yAebmJ/q1T8bihh0WOaNiGUgC6kEDQgnvpyim+HbEmT8RCzKoEhWzAsV3sBc5eq5tTfGtmIYjQ8n5Nhr6ajbK2vEyASkKRprfUDdr01FwgTj3cHMnMb5iGO//APaSi1aYyVNsZzIhZs0WuZLkWNr99yRVn7bjjhyQMhYckKGBIJNt17kjfrVDjNsoWa/GaLlW3JKHcxNm6ctPcBsA+InZEYIqoWa9zzgCwGl723kaXrRjg5VvdIj78Fut7C+htqOuiIq3m2OqFg84ULvYo1tN5NtQOuhPsSzoizI5cqAVBsM9spv330rqfE4q+YhtkU4FC1aU8DJ+aSL978NIPA7E+PF5W/DU+tj8j2S8GeAoyKv/AOyGJ8aLzm/DSW4JYr/D88/ho60PIbH4M+RRWq9PBPF9CH5/8qL+yuM8RfPX10+rDyhbX4KS1FarfEcHMWis7RiygsTnQ2Ci5Nr9ArKbQxMkSI73IkaTKVItZHIsQdxtapxal2YnaLShWc93fl/ueulDbnW/kSp7RWaEU6tZsba/WfzU9VOJtsc7t5q/cKNoWaGiNUY24vjt5n8qP3cTxz9G3qo2isuaOqUbbj8f/pvSxtpPjF8x/XRtCy3oGqkbZj+MTzW9dH7sxfGx+Qj76W0LLOjqs914vjY/L/Oio2hZpdmYEQs+X9I2dzvu5+F1bt26pqYZFDZUHKLFugltWNue9zVLsSGaEs7yFlkCtlNrrJrfXXS1h3dVW82N8EZWJa+qg5Vtqcx5r7hXkJ3u72a0RZGWNWc3VFW50NgBv0GtYfauJfFvnUHKgNgSq2U2te53mtXtvaE8agRJmJ1JtmsvYOmqv22MSrBgFbIq3vpp0LzC4GnXWjDaW6iMvBW7C2QJeWXtlNsuXNzDfr101JiI4Z5BILEWGZbkWsDYjp3a1Jix7YYmJhe1jddLgi+txrVXFijHIJ1QtZtL7ibc56bfXV6UpNt9vYXFF7wXx0MfHllIzAoSeWWjffGQb6ki+u/S50FWGxNlz4XEgBwYnRwShOXknkhjYX3Ai/Seg0/g8TDiAeO5Og0zW37jfQ5gfrqfhVCg8tm32v0CqZZWrBIVJA0kTRtI2pYBjq1gxy3JJLaW7gKjyxkKkAJF0IZhc2VAo0JOhN+fdWfxm2mw7s7MDckCO5NwOf8AVHX22vWc2rt2fEXDtZPEXRe/nbvq2GCcv0CzpGw+FOz9ncZG8rvnYELHaQIVBBva1r3Hk8sjE+y5ggSI8PiH6CRGgP75PorjtCt0cKS55FvZ1j/+wQ/7lJb9qt/JlqZhPZawLG0kOIj68qOo8183orjdCpdKIb2eidk8LtnYkgQ4qMsdyOTG57FkAJ7qvSK8sMoO+tHwc4a47BWEcnGRD9FLdkt0Ib5o9Og26jUHh8Mkp+TvG1/zeb9lJ9hq5fOsXtaJ5QxVTP4Nr6zqu49orW7H4aYXaGHmRCY5xBIWhc8qwRrmNt0i9mo5wKpdhIQMLcfpZv8Au0tWnRJxuyvO+EZw4vAc/HD5nqFGJ9nc7yj/ACm+5K65IRzgHtAqLIiHeieaPVW7eZd5y7/00/pnHbDJ+GkGDZ53YlR2xOK6UY4+eKM/MX1UlsNhzvw8R/y09VSsj1Uc0bBYD/eou+NqI7MwXNiYO8EfdXRzs3Bn/ZYe6NR9QpJ2JgTvw0fcCPqNFj6qOce5GF5sRhvPA/00XuLBzT4b6Va6KeC+zz/s47nf8VF/YrZ5/REfPb7zS3Iamc4bYkXNLAeyVPxUjg3sVZ5pULABFJBHKB98C6G+o1310huAWAI8GQdj+sVm+CGBWPFYlF3KJEF99kxKqL9dqSafYkpWNf2Th+NXzR+KhV/YdFCpBZExOxdotIMqxCMbxx0ZZus3OnZSNq7Bx0kbIiAEjeJ4RexHJPLvlIv5Bvua0AxcXxieevrovbUfxiecPXXn/h4KuDp9NeTN+4e0VhVRCHkAAuZoeveeM1A0HXVLguBuOEqnEYYGPlA2lhNrqbEBZL77eWt8Jk8ZfKKZmYcxB76ksMUnXuHST9zA8IuB+MLg4eF3UjVeMj5BG6xZ9QejW1j1VDw3BfaioUOGkCkgkXjIv06Ma6QoJpfFt101GlQdFGOw2w8Uo5cDnpsrX9AqNwkx0+EVCMys5sEdLZlW1zqNRcjdbeK3LAgEnQAXJ6AN5rjfCLaxxU7S3OUcmMdCAmx7TqT29VKOCMpWyvJBQRBnmZ2LuxZmNyTvJpuhQrWkZwUBQoUxh0Kciw7sruqMyxgNIQCQik2Ba24X56ZvQAqhRUuCJnZUQZmdgqgb2ZiAoF+ckgUAErEEEEgjcQbEdhG6p+D25i4mVo55OQbqGYuoNw3gvcakAnpqHisPJE5jlRo3XwldSrDuPN101Qn4E0dk4GcO0xh4idVixFuTlPvc1hc5L6q285bnTUHeBq3BrzkjspDKbMpDKRvDKbqR2EA13nYm0RicPFOUj98QMwyIQG3ON24MCKt6+1cogtNvfDokHfRWqyhjiI/IxD/LT1Uv2tF8VH5i+qpfGR8B/D5eSqpa1YNh4vio/NFAYeM/AUdgt9VHxkfAvgJeURY6lKaS8KDcD5zeumJFPNp85/xVF6mL9iS0U17onX0rCcF1/veK7Zv+6Wtct/6aT8dRodmQIxdIlVmvmIaW5zHMb8vnIvQtRFE1pZr3RW8UKFW3tSPxP35fx0Kl8VD7j+Fn9jnGC4Fe/wAoCggBGUZ5NAQ2a3eOeph4CT8yi3y3royOeOZebi1PYczg/d5KlVl6rNagjl/9gsR4i/SH76aPAXFfFD6RPXXVTTZo60h7EcsbgPi/ix58dIHA3GD4H78VdUfdTFHWkGxHHOE+ycRhYQ0oZRI3FjlIbkgsRZddwNZIV0j2ZZz/AHSPmPHP3jilHoJ8tc3qSdqzNl4lQKt9g8HcRjFnaBbiCPO1/hHUiNOlyAxA6usVTu1hc16F4E7IXA4GNGsrFeNmP+I4Ba/TlFl7FFV5Z7FYYse9nnpTfUUoVb8MsAIMbiECFFL8YineqSgSAabrZrW5rW5qibG2XNipkgw65nc6eKoHhO55lA3nuFyQKsTtWQap0dL9hPAWjxU5GjskIuNCI1LN2j30DurLeybwYTBYhWhW0E4LIOaN1IzxjoXlAgdZG4V2fYGyI8Jh48PHqsY1Y6FmJzO56ySTWW9mSBW2fmO+OeNl+deM+hz5KyRyXlvya5Y6x/dHEqtOCuHMmOwiLvOJibuRw7fuqT3VWwRM7Kkas7sbKqAszHoVRqa7L7HHAZsJ/ecVb2wykIg1EKtvuRoZCNCRoBcC9zWjJNRXJnxwcpcF1ws2BhtpwtGroZoweKkUqzRt4rW1yE6Ed+8CuASxMjMjqVZGKsp3qymzA9hBr07icIkls63I8FtzKelGGqnrFcH9krCNFtGYNqXEclx8IFAuYgAAElDcDS9yLA2FOnlztLtRH3MxW44O7Qx8OGjSI2SxZQUvo7F9+U6HNffz1U8C+CkmPl3FYEPvsnN+zQ87nq8EG55ge1LsgAAKwAAsAF0AGgA1rS5JFeKL7nPk4SbVG7J3p/8ASlHhZtMb+K71P4a3jbKPj+j+dJ9zD4/o/nUd8fBdT8nPcNw62mzMpSDkm25ufUbj0GpLcNdo20TD36w9vQ9azA7MPGT8oflF5t/vMdTRsnrXyU90PAVLyYH+3G0+eHDHuf8A8lOLw32hzwYf/qfjrctsb5PkpI2EOhPN/lRuh4FUvJixw4x3Phoe5m/FShw5xnPhY+6Q1s/cBfFj80eqiPB1Pi4vNH4aN0PAVLyY7+3WL/3RPpf5UK2H9nU+Li80fhoUboeA9RYoPfj+zX7b1KqJGffmHRGnpaT1VLqosQDTRp002aiMQ26mDT7bqYoA5/7MuH96wsviySR+egYfwjXL67d7JGBMuzZSBrEVmHYh5Z8xnrlOE4K7QlhGIjwsjREZgwy3ZelUvnYdBAN+arYSW3ky5YvcI4K4ET43DQnc8y5h0qnLcd6qa9E4iIuy38FeUR0uCMl+oantynmrh/sUwhtpxX+AkrDqOQp/rNd3rPqH6kX6Zels5V7JfBSefGpLG0d8QYsPCl2Lu4DF2YZbKiqCxa50XdrU7buB2HsaOPDz4Y4vEyLnZr5ZVG7jA+YGEXBChNeSdbgmtlhsOJNqozC/tfBsydT4iUIWHXlhI+ca47tiKTam3JYQ2UyYl4FYjMETDhluFuL8mJmtcXJ66uxNuKKsqSkzofBDE+2XucTNLh+LSXDpJkBy5njkTEMozSyRultWIIZGNyb1oeEWwYcbEIZy4QOHIRspYqDYE2Omt9OgVifYjRl42Jjcwz4uLq0ODBt1ZgT310ms2XifBoxLdDkrNh8HsHgwRhYVQnQtq0jDoMjEsR1XtVNw928uHVEZ5I0cFpXitx2QWAigJICyOT4XwVSQ6ECtbauXeyrhWxGOwWEQhTPZQx3AhyLm2+wkJox+qasMnphwWWzcXB7U90NkNJGiSCLFQYl5JgoZlUzENIxDIHWTksAy5gddznCjgFHiJnxM8ztlhWNEFlLMoblSP1s17KFt2aVRew9gy/utgJdzRcW4B0DAzwuR6Nf1RW82ljv7rC7AnOYC1raAZZZGN+YKjk9lXZfTJOJTiSkmmTMPh0jVY4kVEUWVVACqOgAVKUUzTybqZcE4pk0++6mGpARcJ4cvyx/CjqalQsH4cvyx/CjqatMAzQFEaMUALFKpIpVAgUKFCgRBQe/N+zT7clSqhRS3ndeiKM+c0vqNTaY0A02aWTSCaQxD7qYp591M0gE4yMPHxTaiUiNh0o2kg8zPVhJiAjIpACtyUNwAGAJCW5rqptbot0Xg4lsoV/EdD2AtkYnqCsx7qXtaEsyAWuUlVCdwm97kjPdxTG/VVOTuSRWDgyqbTXHRKAHilSYDQcYchWQDrAYHrAPOa0wohRiq22+5JRS7DGFQJjFc7pIWiv8ArI4kRe8GU/NrhO0J59m7ZmmCjjI8TNKgcHKyTGTKea4KSHUc/ZXe5YlYWYXH3g3BBGoIIBBGoIqu2lsZJyvHrDNk8EzwJK6joVjbTtB671fiyqKplGTE27RkfYkwDJCZHzFpc85ZvhceyqD3jC5+yUHnFdBAprDQBAbakm7E2uxsBc2AG4AWAAAAAsBTt6qyS3SsuhHbGg7Vzn2UWeCbC4+Ncxwsik3vl99zZc1twvBa/S46a32NeQKWjykgE2e4BsN2YeD22PZTc6cYgcRo4ZLNFL4EiPYlX0NiCAQbHnHPcPHJKVsjlVxpHPfYUidV2jj5BowAB8ZxxksoHe6d5rX7ZhtCY+ZMJN5wjWNfQz1ZxxchIY4Uw8EZBEaW1KnMoAUWVQ1m33JHML3hbYc8dFGFNpVbM2lgsLxuQflZivfVmWW6SSK8cXFNsmNvNOpTNOrViJhvTJp5t1MmkBDwnhy/LH8KOp6VW4H8pP8AtF/gx1ZLTABoxRGgKAHBSqSKUKBAoUKFAqMmu20XFSkQzsTFEpATUBS7Bst7i/GfVVodsf8AD4j6MfioYCIJi5cot/d4R/1MRf6h5BVmak2gVlZ7sf8AD4j6L+dJba3/AA+I+hPrq1vSWkbpPlpWh8lV7rA6cTiB1mFrVD2rwhhw0ZlmWRVGgHFsCzG9kW+lzY+mr9pDbefLXFvZR2y8+MMOYmPDgKBfQyMAzt26hfmnpppJsjOW2NjG3OHmOxOZVfiYiCMke8qdLPIRmJt0WHVXROAfDmHEQrFiZVjxCAK2chRMBoJFY2BY867730tXExQtUpY4yVGaGaUXZ6OPCTB8fHhlnRpZM2VUYNbKuY5iDYEgaDedeirevMux0viIApIJniAKmxBMii6kbjXo+DEWISQ8o+C24Pz6dDWBNuokaXtmyYtvY14su+7JdFR0RqkvBQrKcL8L74kjaoy8XY6qrqWYG267BiL/AKgHRVE+z4WBDRJY6eCAe4jUGnSNGPTvJG0zouIhDqyMOSwKnmuCLEeSnBXJdl7JmkxPtaKWVAtnZ0d0KQncbqRZiQyjpIJtYG3WqGqKZR2umC9Y7h1wnjwM2FLoXzCbMFIzKnvfKF9DrbS45+itVjMXHEjSyuERAWZjuAH9bq8+cM+EJx+KaYAiMARxKd4jW5uR4xJJPaBzVZhhulfsZs89sfudpwPCHCTIJIZcyn9Vrg86sLclhfcamLtOHxx5D6q4dwK4SNgcQGJPEuQsy82XmkA8Zb36xcc9dzxRbklD13+o9laHGiGOe5Dcm2cOBrKPT6qjHb2FAJMy2G/ffuFrnuqZx7jn9AoR4gg3IBvvuBr6NKXBPkotl8JsJJNiFEqjI4F2uqtZApylgAeUGHpq6j2ph/j4vpF9dVmB2ZAZsQ7QqS7pqLjURqWJA0Nyb+WrZNnQ/FrTdCVh+6EJ3Sx+evroe6EHxsfnr66X7UiG6NPNFLbDRH9GO64+o67qXAciF2hD8bH56+uljHw/Gx+evroDBReIPK3ro/aMPifvN66OAtg9uxfGJ56+uhQ9ow+J+83roUcCtkWEf3lz/gxeiSb11OIqHF+Xb9lH9uWpjUiYRpmT1fXTppibd30gFnrrzfjsSZZJJSb8Y7v57Fvvr0BwhxXFYTEy+JBKw7RGxHptXKuAXAQ4tRNiCyYceABo81t9j8GPmzbzzW31ZDi2ynMnKkjGXoxWk9kZoRjWigRUjw8aQBVFluM0jdpvIQT0io3BvgnjMcQYUyxX1mfSMdOXnkPUveRVl8WZ3F3RN9jXZRxGOja3Ig9+fouNIh2l7HsQ126RFYEMLg8x8oqs4NbAhwMPEw3Nzmd2tmkfxmtzDcBzDvJsZ5QoBO8kKouLu58FFvzn+tKpm7Zqxw2x5GXxMkLRoPfVdmVVZgJRlRnOVm0k0W3KIOtyxqww2LRyQp5Q8JGBV15rlTrbr3Hmp3DbFQp7/wAqQkMWUleLIvlWJhYgC5F/hXN9DYJxOxma13WUA3XjVs6k86yx2y6dC366rlhfsOOZCcThkkUpIoZTvB8o7CDY35rVTHgvHfSaUDo97Nuq5S/luasnweJTwBI3QM0Uqd5kZJD51MA49myrGoIKhiyR2RWOrMFxRbwbkC2tu+q1jkXR1G3syTs/Z8cC5Y1tc3Yk3Zj0sx1P3DQaVXcJeFWFwKFpmJa+URoMzliCwU8y3AJ5RG6pG1IZI5EWafkSCyZPeQZFuSl8xYkrqAG+A9QtpbGgnhbDyIOLbmUAFWvcOvQwOt6ksXPqIvI5K4nHOF/DHEbQaz+9wqbpEpuL8zSN8NvIBzDnOdvWh4S8DcXg2JKGWHeJUW4t/iKNUI69Og1S7PxpidZECPbergNHIp0ZHXcVI09I1ArXFJLgwS3X6hg13XgFj+P2bhmJuyKYWvvvCcgv2qFPfWIxPAuDG4f25shiL3z4V2vkcWLRo58Ei9wG0IIIIBFXvsRs4w2IhkUq0WJN1YEMuaKPQg7tVNKTTRbiTjI2zCkWpw0g1UaRrAjlyfLH8NKslqtwXhyfLH8NKsloABFAUDQFADi0dEtHQIFCjoUCK+P8u37KP7ctS2NRI29/Yc3FRnyvLf6hUpqCQDTE1PVHncAXJsOukA3tHBpNE8UoujizC9ri4JFxzG1G+dY24lVzBSI1PJS4FkBsNF3bhup47qC0AYzYfsdYaNuOxrnFzMxdswtDmYkseL+Hck+Fp1CtqNwA0A0AGgA5gBzUhjSxTbbFGKXYjY3GCOwAzO18q3te1rsx5lFxc9YG8iq4IHJLNncWuwOqHRhkGvF2IBHPoCSTrQhbO7yH4TFV6kjJVQOonM3z+qjxGGzcpTlceC3+lh8JT0d4sbENI6OHClG2rNRsjaXGrlfSRRyuhhuEi9R5xzHTdYmxzViMJiG0ZeRKhsecA84PjIw7Li24jTRy7ZQQ8aBdicgjvrxtr5CegDlXt4OovVqdnO1Gm2S9PZ/9Qnbe1jF73FYzML66iNDccYw7iFHOQeYGqHDBozniPvgNyzG5kJ8ISH4QPo0I3CginVmOZmOZ28ZrAdwsAAOYAClioWdDDpYxhUlyy52kUxeEZlW5AzhCASJI9TGR0nlJ1hrjQis8khQBo3GU2srG6G9goU70vcAWuBfwTVlsjFcVKL+BKQrdT6LG/foh7V8WqAQEPCBbKudT18UCIxbvJ+bTfJThxbJSxyV+C/wmKDgkXBBswO9Tv8liCD11X7T4LYDEEmbDRljvdRkc9rpYny0pHyyoeaS8bdoVnQnsyuPn1aiodirNj2yplDsDgjh8FK0mGkmUOuV42cNGbeC2q5sw11vzmr6RRvsLnebamw0ueelUUg3Uu/cqSS7DBolo2okoGNYXw5Plj+GlWC1X4Tw5flj+GlWC0AGaIUZoUALWjFJFKFAg6FChQIroh7+37GP7ctS2rFYDhZiWxskDbPlEgiU5c6qQgdrMWewIPGAaHeO21221cZe3uZOO2WC3lz1LYwUkW9QMUz5wAOTzmo7Y/Gjfs6TumgP+umJMfi//AG+X6WD8dLax2i6G6jWqhdo4v/2+X6WH8dS8PicQw5WEdT0GSE/U9G1hZLalrUGXETDfh28+P8VAYyX4hvPj/FSodkLZ35JPkipIqFsx2ysrrkZZHBW4bKCc8YuNDyGSplTR18buC/Qj4vkssnWEf5LGynuYjsBaneKXNntyrZb9V729FHPEHVkO5lKnsItTeClLxox3lQT1EjUeWgdcj9CioUEgOoYEHcRY9hqLiEyqhuTkddTvOb3tmNtL2cmpdRtpn3mQ9EbnvCkigTXuKxJ8A9EsX70ip9TGrkVSY7RCfFKv5jB/9NWhklv4CW6eNH1WqJh1fzIk0JDupCsefKPng0jEO4IyKjDpMoXutY0jIIY01FJra3NRMJ+ZIvpx+CmZYsbvjhhbTmmLHyBRRQrHsGeXL8sfwo6sVrEbN21tD2xMvtDOFcZykhNjxahSDlsQQAbb9T0VoI9o4sj8zP0y/hpuLEpIuKFU8m0sUP8AY9d/5YW8uTSji2pMRrhwp6ONv6RHRQ7RcClA1VLjpz+gX6U/+OljF4j4hfpT90dFBZZ0Krfbs/xA+kb/AMdClQWMRxg46ST4QgjF+oyMfrQVZSoDqdT161XYVh7cmGtxDB2WLTW+/wBFWT02CGCg6KjyCpLVGk30hj0YFhSso6KTEdB2UugBtgOinABTTGnUNAFbj48kysN0ilD8tLumnyeMuf1VpdObYHvZbxGV/mqwz/uZ6bpo6OllcaBUbBC2ZecO/wC8xceh1qTUaI2lkXpCP5QU/wDjFSND7kihQoUDBUbaX5Nh41k75CEHpapNRp+VIi8y3kPcMqg97E/MoE+wvGR5o3XxkYeVSKtIArKGA0YAjvF6hCn9j/kUHirk+jJT/TSZk1a7MlCNegUGjHQKUKNv68lRMIXFr0CklANwp2m2NICDs5Mss5GmdkJ7owKslqFh/CftH2RU1aYAKi96QIE8UU6RQoASIl6B5KWqDoHkoCjoEDKOgUKFCgClwQ/vuIP+Dh/rmq1eqzBfnmI/ZQfamqzemwQw1R5N9POdajsaQx6HcOynCaaiOg7KUxoAQTTybqYJp5DQAJog6sjbmBU9jCx+uqzByFo1LeEVGbqa3KHlvVtVTGMryJ0NnHyZOVfszZx82mjXpJepoeqJjOSySc1+Lb5MhAU9zBe5mqVSZYg6lW3MCD2EWOtSN0uwqhTGClJQZvCF1bm5SmxNuYG1x1EU/QNcgqNhdWd+lsg+THcW8/jPLUhnAFzuGp7KYwCkRpfeVBPadT6SaQn3JNO7H/Jn9pN6ZnP301TuxvyX+ZN/GktQzNq/lRNFKbm/rmpK0pr6W6fRaoHPF0y9PGmXoAjweE3aPsipyVAg8Ju0fZFTloAUaAoUBQAqhQoxTEFQo6FAFLgx/fJj/gQeh5/XVo9VuD/O5v2UX2pKspBQCIkp1qO2809NvqO530xj8R0HZSnNNwnQdlG5oAImnYzUd2tUTa21Uw0RkIux0Rb2zudwvzDnJ5gDSY0m3SD4QbdjwqXIzSN+TjBsW/WY/BQc57hc6VkNgbVkOKLzPmaayMdwBuTGFF+SoJKgfr3NySapMRiHkdpJWzOxux3dgA5lG4CiU93ZvHWKhv5O/p9AoQ9XzP8AwdSFCq/Ye0OPiDHwhyXH6w3nsOhHbVhVxUZrhJi58PIJImAWUWYFQV4xdzdNythv/R1UNwmxZ+Eg61j1/eJFafhTheMwz23paQfM1YDrK5h31garm2jTp8cJJposfdPEysqNM5DsqEAKtw7BT4Kg89dCrnWwkzYmEHx7+apcfZroopwbaIZ4xjKkvYTNKFUs25QWPYBc1L2dEUiRW8IIM3yiLt6b1XYxgTHGSBxsgWxPhBQZHXruiMO+rdnHTTZytXLlIVHTvR/XNTEbjpHlp3jF6R5RSMY4aYfdSmnTnZfKKjS42IAkyIB1uvrpAJw55b9o+yKnrVJsrHxStK0MiSKCoujq48Ac6k1cxNcUwFmggtQvQvSEKoCk5x0jy0BIOkeWmAuhSc4oUAYbZHBdUx8+bEYl8sEXFsZ2zhZGfMrHnF49OitFJsFPj8T9O/30zhSRtCUcxwsJ7xLKB9o+irl6k5MSiiil2TGDo83fNIf9VNPs1LnlSfSyfiq0m31EmvrbfRbHSG4dmRcm5k+lf107JsnDHeJT/mtT0R0HZRuaLYUQptnYJFLFXAUEljK1gBqSa55tDEiWRnAKrujUknKl9L33MdCe4a2FaThttCwWBT4Vnf5IPIXvYE/M66ydQlJ9js/+ZpV9V/j/AGCjFFQFV0douODu0eJlFzZHsr9A8Vu4k9zHoreCuWg1uOA2bECRZXLLEECqCVNmz+Gw1bwQB1DW9SjOlyc/Vx2est7hiUUZz8JRzX8YnRdOnfzVzPFYVoXaJxlaNspF77vBIPOCpBB6+au1wwIihUUKo3BQAB2AVjfZF2RdVxSDVLJLbnjJ5LH5LHyOxO6oOe50Y9Nqqyc9nwZrgnC74lckbPlDM2XKMgKlQSWIGpNrb9/QbbyWORBdo2A5yMrW7lJPopHATZnE4VXI5c3vrfJI97XuWxt0lumtC9HUa4IZ9U5ZG49jlXCXaaviEy2dILNpqHYlXYdBGUKL9bVuhs7DEBljUhgCD0gi4Ncz2pGFxGIAFh7YnPlmc/fW84H43jMKgO+ImI9i2KfuMnpq1SsNZi/lQyf3/PJZR7Mg+KXyU+my8OCDxS+n6r0uOpAp2zmURzs6A6GFDfq6abm2Th2BDYZDbfYEHyg3qdG9ua/o5wd9j0W76b44i559/fp07xoPJTsi19ijw3BrBLI5TCxANlOtnN7dDE9N++rVNkwD9BEP8tOrq6x5abgc5zruy/Vb7h5KnK5t/XV6qLCmMjZ8XNFH3IvV1dY8tGMFHzRp3KtOhz0/0LeoeSgGNIORoYJD8BPNWj9poPgKPminQxo6LHyN8WP6FHS6FAyig/P5P+Vj/ivVs9HQpsSIE2+ozbzQoUhjsW4dlHJQoUxo5/wr/OZOxPsLVQKFCq5HptD9GIKFChSNYa1tvY08PEfJh+uahQqLMWv+i/x+5vhVXwq/MsX/AMtP/CehQqtdzz7JmzPyEP7KP7Ap6ShQpS7hA47tv85n/bzfxGrTcAfycv7QfYWhQq+B1tT/AEkfx+xro6foUKmcQI00+6hQoAjxeE3zfqNTVoUKADoChQoAMUqhQoAFChQpiP/Z"
                class="card-img-top"
                width="160"
                height="160"
              />
              <div class="card-body">
                <h5 class="card-title">Shizuka Minamoto</h5>
                <p class="card-text">
                  Shizuka Minamoto (源 静香, Minamoto Shizuka) adalah tokoh animasi dalam cerita Doraemon. Shizuka adalah 
                  teman 
                  sekelas Nobita dan temannya sejak kecil. Ia 
                  punya sifat yang rajin, baik, manis dan aktif. Ia akan menjadi istri Nobita saat ia sudah dewasa di masa 
                  depan.
                  
                </p>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAACQ1BMVEX////u7u7t7
                e01eZfpwlTUJ0wAAAD39/enpab09PQgpd77+/v1bVFaMCqYMD/x8fEzIR4dEhZnWjgpGxrRGi9eMishFRcfquX79ydXLynl5eU4
                g6WGlWazsrKsqqvI4orc3NwTAACioKHT09OioXo5haf/2V3vyFbGxsa9vL3cJ00jsu8tHRydMUEbAACbmZoAAArnJ055eXmvLUQ
                2dZHvKE9dXV1SUVItGBVAIyFNKSQABAAlAACJiootAAASDQ/4nq4ti7VqamoAABLJKkUol8j/3V9LPipZTjDB14iMnGr4+rZCAADQ
                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"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Doraemon</h5>
                <p class="card-text">
                  Doraemon (Jepang: ドラえもん) adalah karakter fiksi dalam serial manga dan anime 
                  Jepang dengan nama yang sama yang dibuat oleh Fujiko F. Fujio, nama pena dari tim penulisan 
                  Hiroshi Fujimoto dan Motoo Abiko. Dia adalah sebuah robot kucing yang melakukan perjalanan waktu
                   dari abad ke-22 untuk menolong seorang anak laki-laki bernama Nobita Nobi.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/png;base64,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"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Dorami  </h5>
                <p class="card-text">
                  Dorami (Jepang:ド ラ ミ ど ら み Dorami) (lahir pada tanggal 2 Desember 2114) adalah adik perempuan Doraemon. Dia berwarna kuning, ekor bunga, bukan ekor rubah, 
dan memiliki pita merah besar, bukan telinga. Dia kebetulan sekitar 2 tahun lebih muda dari Doraemon. Anehnya, mereka adalah saudara kandung karena fakta bahwa mereka menggunakan jenis oli yang sama.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="https://www.monster-strike.com.tw/entryimages/0do1muriuhiu_12.png"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Suneo Hunekawa</h5>
                <p class="card-text">
                  Suneo Honekawa (骨川 スネ夫, Honekawa Suneo) adalah seorang anak orang kaya dari keluarga Honekawa,
                  akibatnya ia sering memamerkan barang miliknya pada teman-temannya, yang membuat teman-temannya menjadi                     iri.
                  Ia berpenampilan memilki wajah seperti rubah. Ia bercita-cita menjadi perancang busana terkenal.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="https://i.pinimg.com/236x/ff/0f/e9/ff0fe97f0cdf2dc63a12e5c4d9395920.jpg"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Nobita Nobi</h5>
                <p class="card-text">
                  Nobita Nobi (野比のび太, Nobi Nobita) adalah tokoh protagonis utama dalam cerita Doraemon,
                  Ia adalah anak yang kurang beruntung sampai Doraemon datang dari abad ke-22 untuk membantunya, 
                  sehingga ia bisa memiliki masa depan yang lebih baik dalam kehidupannya nanti.[
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxITEhUTEhAWFhUXGRoXFxgXFxcYGB
                cYFRcYGBgXFRYaHSggGB4lHxUYIjEhJSkrLy4uFx8zODMtNygtLisBCgoKDg0OGhAQGy0mICU1KysrNTItLS0tLy03LS0tLS0rLS
                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"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">takeshi Gian Goda</h5>
                <p class="card-text">
                  Takeshi Goda (刚 田 武 Goda Takeshi), lahir tanggal 15 Juni 2001, biasanya dikenal dengan julukan
                   “Gian” (ジャイアン Jaian) sebuah kata dari bahasa Inggris “Giant” yang berarti raksasa, adalah anak 
                   pengganggu berbadan besar, kuat, dan cepat marah .
                </p>
              </div>
            </div>
        </div>
      </div>
    </div>
```
## Body -> Tentang Syntax
```
<div class="container-fluid pt-5 pb-5">
      <div class="container">
        <h2 class="display-3 text-center" id="Tentang">Tentang </h2>
        <p class="text-center">
        CERITA DORAEMON
        </p>
        <div class="clearfix pt-5">
          <img
            src="https://asset-2.tstatic.net/jambi/foto/bank/images/doraemon-nobita-shizuka-suneo-dan-gian.jpg"
            class="col-md-6 float-md-end mb-3 crop-img"
            width="300"
            height="300"
          />
          <p>
            Doraemon adalah robot kucing dari abad ke-22 yang dikirim oleh cicit Nobita dari masa depan,
            Sewashi; ia memiliki "kantong ajaib" yang berisi alat-alat dari masa depan yang biasanya digunakan
             untuk membantu Nobita. Nobita sendiri merupakan seorang anak sekolah dasar yang malas dan kurang pintar     
             meskipun berhati lembut.
          </p>
          <p>
            Beberapa nilai moral positif yang terdapat pada film kartun Doraemon, 
            antara lain: Kasih sayang, Tolong menolong, Kerja keras, Kontrol diri, Kepedulian. 
          </p>
          <P>
          Doraemon merupakan manga populer yang dikarang oleh Fujiko F. Fujio sejak tahun 1969
          </P>
          <p>
            Doraemon berusaha memasukkan nilai-nilai anti-kekerasan, non-erotis, 
            perlindungan lingkungan hidup, integritas, keberanian, kekeluargaan, kehormatan, dan kegigihan.
          </p>
        </div>
      </div>
    </div>
```
## Body -> Tim- About us Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="About Us">About Us</h2>
        <p>
         Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illo, rerum exercitationem iste eius nobis quos, rem 
         consequatur et reprehenderit in natus. Ad deserunt itaque, doloremque repellendus ducimus ipsa qui magni.
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4 text-center tim">
            <img
              src="https://cdn.gramedia.com/uploads/authors/Fujiko_F._Fujio_EHskHPX.jpg"
              class="rounded-circle mb-3"
            />
            <h4> Fujiko F. Fujio</h4>
            <p>karang/Pencipta </p>
            <p>tahun 1969</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-instagram"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoOm1xjmMwOht_I3zJZRwjRkMW4RHnyerd_g&s"
            />
            <h4>Hiroshi Fujimoto dan Motoo Abiko</h4>
            <p>Penulis</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-instagram"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="https://w7.pngwing.com/pngs/171/327/png-transparent-doraemon-desktop-doraemon.png"
              class="rounded-circle mb-3"
            />
            <h4>Doraemon </h4>
            <p> Peran utama </p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="https://www.youtube.com/watch?v=c2_ZGNLILgo" class="social"><i class="fa-brands fa-youtube"></i></a>
            </p>
        </div>
        </div>
      </div>
    </div>
```
## Body -> Client Syntax
```
<div class="container-fluid client pt-5 pb-5">
      <div class="container text-center">
        <div class="row pt-4 gx-4 gy-4">
          <div class="col">
            <img
              src="https://cdn.iconscout.com/icon/free/png-256/microsoft-28-761688.png"
            />
          </div>
          <div class="col">
            <img
              src="https://cdn3.iconfinder.com/data/icons/glypho-social-and-other-logos/64/logo-facebook-512.png"
            />
          </div>
          <div class="col">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKuiiyRvMNxSMfZYNb5_b-GkEAAmiJkX071g&s" />
          </div>
          <div class="col">
            <img
              src="https://i.pinimg.com/originals/20/1d/17/201d17590b3a7bc8939ca37e577bbbd8.png"
            />
          </div>
          <div class="col">
            <img
              src="https://www.ictmagazine.nl/wp-content/uploads/2020/10/ibm-720x340-1.png"
            />
          </div>
        </div>
      </div>
    </div>
```
## Body -> Kontak Syntax 
```
<div class="container-fluid pt-5 pb-5 kontak">
      <div class="container">
        <h2 class="display-3 text-center" id="Kontak Kami">Kontak Kami</h2>
        <p class="text-center">
          Thank you for visiting our website. Let me know if you have
          something to say
        </p>
        <div class="row pb-3">
          <div class="col-md-6">
            <input 
              class="form-control form-control-lg mb-3"
              type="text"
              id="Name"
              placeholder="Name"
              required
            />
            <input
              class="form-control form-control-lg mb-3"
              type="email"
              id="Email"
              placeholder="Email id"
              required
            />
            <input
              class="form-control form-control-lg"
              type="number"
              id="No. Phone"
              placeholder="No. Phone"
              required
            />
          </div>
          <div class="col-md-6">
            <textarea class="form-control form-control-lg" rows="5"></textarea>
          </div>
        </div>
        <div class="col-md-3 mx-auto text-center">
        
          <button type="submit" class="btn btn-danger btn-lg">
            Submit
          </button>
        </div>
      </div>
    </div>
```
## Body -> Footer Syntax 
```
<div class="container text-center pt-5 pb-5">
      PUTRI YANTI &copy; 2024
    </div>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
      crossorigin="anonymous"
    ></script>
  </from>
  </body>
</html>
```


## Full Version Syntax 
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>company profile</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
      crossorigin="anonymous"
    />

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
<!-------------------------------------- Navigasi ------------------------------------------>
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top"
    >
      <div class="container">
        <a class="navbar-brand" href="#container-fluid benner">Welcome To Animasi Doraemon</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse text-right" id="navbarText">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#layanan">Layanan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Karakter Doraemon">Karakter Doraemon</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Tentang">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#About Us">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Kontak Kami ">Kontak Kami</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
 <!------------------------------ banner --------------------------------------->
    <div class="container-fluid banner">
      <div class="container text-center">
        <h4 class="display-6">Selamat Datang di Website Animasi<span></span></h4>

        <h3 class="display-1"> Hai...<span></span></h3>
        <p>Salam Hangat Dari Kami & Semoga Sehat Selalu</p>
        <a href="#layanan">
          <button type="button" class="btn btn-danger btn-lg">
            Cek Layanan
          </button>
        </a>
      </div>
    </div>
 <!------------------------------ layanan----------------------------->
    <div class="container-fluid layanan pt-5 pb-5">
      <div class="container text-center">
        <h2 class="display-3" id="layanan">Layanan</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate,
          doloribus.
        </p>
        <div class="row pt-4">
          <div class="col-md-4">
            <span class="lingkaran"><i class="fa-solid fa-heart fa-5x"></i></span>
            <h3 class="mt-3">Pesan Moral dari kisah doraemon</h3>
            <p>
              kasih sayang, tolong menolong, Kerja keras, kontrol diri, Kepedulian. Digambarkan saat Ibu Nobita merasa 
              senang karena Nobita telah kembali, hilanglah rasa khawatir seorang ibu yang sekian lama anaknya entah dimana.
          </div>

          <div class="col-md-4">
            <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
            <h3 class="mt-3">sejarah Doraemon</h3>
            <p>
              Lahirnya Doraemon bermula ketika seorang komikus, Hiroshi Fujimoto (Fujiko F. Fujio) 
              bertekad untuk membuat serial komik setrip baru di sejumlah majalah sebagai pengganti komik setrip karyanya 
              sebelumnya, Denka Dari Planet Ume (Umeboshi Denka) pada tahun 1969.
            </p>
          </div>

          <div class="col-md-4">
            <span class="lingkaran"
              ><i class="fas fa-i-cursor fa-5x"></i></span>
            <h3 class="mt-3"> tokoh utama</h3>
            <p>
              Doraemon (ドラえもん) , Nobita Nobi (野比のび太) , Suneo Honekawa (骨川スネ夫)
              Takeshi "Giant" Gouda (剛田武、ジャイアン; nama panggilan: Jaiyen)

            </p>
          </div>
        </div>
      </div>
    </div>
<!---------------------- portofolio------------------------------ -->
    <div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="Karakter Doraemon">Karakter Doraemon</h2>
        <p>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Id, delectus tempore 
           consequuntur porro mollitia maxime amet ab, quod autem earum eum doloremque ut officia 
           saepe eius! Aut totam et facilis!
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/jpeg;base64,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"
                class="card-img-top"
                width="160"
                height="160"
              />
              <div class="card-body">
                <h5 class="card-title">Shizuka Minamoto</h5>
                <p class="card-text">
                  Shizuka Minamoto (源 静香, Minamoto Shizuka) adalah tokoh animasi dalam cerita Doraemon. Shizuka adalah 
                   teman 
                  sekelas Nobita dan temannya sejak kecil. Ia 
                  punya sifat yang rajin, baik, manis dan aktif. Ia akan menjadi istri Nobita saat ia sudah dewasa di masa 
                   depan.
                  
                </p>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAACQ1BMVEX////u7u7t7
                e01eZfpwlTUJ0wAAAD39/enpab09PQgpd77+/v1bVFaMCqYMD/x8fEzIR4dEhZnWjgpGxrRGi9eMishFRcfquX79ydXLynl5eU4
                g6WGlWazsrKsqqvI4orc3NwTAACioKHT09OioXo5haf/2V3vyFbGxsa9vL3cJ00jsu8tHRydMUEbAACbmZoAAArnJ055eXmvLUQ
                2dZHvKE9dXV1SUVItGBVAIyFNKSQABAAlAACJiootAAASDQ/4nq4ti7VqamoAABLJKkUol8j/3V9LPipZTjDB14iMnGr4+rZCAADQ
                Gz6ffGXzk6IoEhfse4/gWm8AITAmVWsAFihCPj8wMDCAIS8eHh4AGxpUAAAcKikAOVLuZVb/KVKvlUbDpkjZuVImXndfV0RHOAAmJ
                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
                Sv4fxbiYt9V+aoSR0Gp1WPlrhlNaUJGNvlkAnkUH6pU/NmuYSbHZJRIxhu+ennt8Ue2woUlNhWUwvUPt5Yr1zWYVwixUz2MqmeszgbbWempE6SUa7cV8NlQSzRU2MBqeVU8uvfiHT+/D+OdffPH1n5ZhMKTtS1S3NYyWA462V4wg4EXXT1kefrm9Ey2VRTFsq/XUiPJZHgcdgjrDgUIS5GTvEJw5PTIhS3pueuXrr14i8tWWNvi0TaToldnbSx1QJ76ZRrO5tSMN1kfmH5r62o5X46K/mW00qbF9qJBsr5sJ/voxuhWUxz0yH5HPlQwzMFhNhb6i+ptSLXZOoje15W7tTIPRiFwd7JpQHiMZMqkxOVlEY/UBVwieubi2Bp+/pMs6L3elR1VU6CtqDggrKvOvpnKU9+GznWmwPrr10PaChOiJ7aCcJ6QQDgXbMZnjqXCMSfm5MclAX/pKUSIZbQ/IRXR5TeErbhjPtDOPvxXz1MMb22dq5YBqjfgChORHCysdG6EhYju1VRtv/Vkx0q/w33n44k88RfHFyir0FYPtBmsoKYt7V/Lrz48SZomcVVY4vxih1UHHctd8mqm2t2N19UjeAQzzy2OqmX612fPFS3/JYsLXWLkX9gZ95i5t/i08JxWtALhOdlozthcllN5n74ahdgUSI0bjI2leiYavX/p8+LM/ff71139Zh000VvSIvLbR1qzCzmE9DahkppPVRpyqAs6jZ7Nm2RfWoUVa9eBgcsNTo43SaXTJ3sKsbB7MMGrw87/eGhv761+/eOmlL26whl5otkLfBhcf3kPCaGRrOOywQ4E4t71Z9UDHOOh5NDRKDuUpqlsSsnDra6UXIuow+m5Wc6SmdMY3BVYbyFZekbC3sCPCaGT9WpjJd5t3l7/gSk4blg8styJnM8oe2gCsD3/2l6+/+AqTmuG/br6lq7DRFPCkdTR0ri6ZHPWNqoQmK+5d2UGkiEQX3gEebsxv8bZaVyrUshrX6rRh9R0gom1t5v781ddjN5fHLq+Mf/VSMGRIZ8wZqTQ8LTxK1k3p+1RNLygu1w4YnR/vWVl+thBZwFzPUvsM6XMJDd3Wq07/WT/7M9rn/AIx0xsc7VgZrajCScmq/bO+DUP60LtbwvrFRWKnkUXwS63dD0KaV6cMvA9vfPF1z/BLX319kydFhaZC4wmYUyDNEQXEoOFISZMn8hX/uINoGJUKp/qg8oiQ/SCkBG10xCmQfvlnaQUcnVNP6DOq0Fe3kpc+EGu3IV6YS6jO2fGdxvvoLZ527h8hbdxmGUsJKenHcKXS3ueDsEDipy03ZQwXJkfTWWHkIrq4HV/khgq4P4QUazpFUZFspdGZISwbWELIXjNmbebiohPKgkW0fn47wvWHXnWd+74Q2hy58kXu3qWhsmjfO0RWzXLSmuJGY1paUud3lyHUz1f3PajBt5z6ww50wheKh6YEgQrnyvflM2rSYggEQ0Wy3JIPGcdupJeYM56pZyVGGq3f2kaB2AfJQxaVnKT6qRE1nM+gUJaMcFCWLBSLLouJL5ZyaUed6s0fIh3Wm49T/mtGEy2dcJstGeOORm9XzwAQUJ7d9D7n1AhLpbzUlLU5sNk5yAuatqRpVCfFkJoxOaskNpZALJ4FKHCaGWr5mG9UWrQQD1KOnKmyKC2OJ+EdY0eM1o9vM7G2CG+Fw7E4q3m7HREaM2/amwU+FGd4MRfWCcmjhHzSAfuTAhXIcnwuX3Bn4wGnf7YsVAzJGxpzJCNPVi8OsXbquLyyoDFFF2+ZeBcMXjUamV+5Pba8fBP0NeO7JUTfoExZYMwTNEJKUEbsk41gp3LASKfToWSLpQP5Q7OSx42BlRKk+l47Lduswc6NYFtTP6iIkXlpQEqJFtHFeRPgZs/W/Pno/OZNfcJit4R+0JdEB5ayDkp+2pVdO6cHK8W4V1s74+1WMjbNz3QWpWMpvKKdIstXk42jQ8VHj6bqMPc2Z62dBXA1IaJsmZGtVillkTQXjc7PRzXEaGRhObO1ubV5+7a+5GPXhAEwrvm2SAUTmSM2nD9P1vuGVZ8aBuW6WtuTUE9+wRFFukaHHgEEOVbI5gBme4eMHbFXzEBHU9PlsahUF90iI9oLm8RQI4vPFupb1biBFgrjm62tb7SOQ84w+r5LQt68Ld2SZ6WZt7wW1dt9vVj2hf0KIqt0Q82J+CT1OnipLTlYYTWHZQtxMGV4pNLUmTaX2NHUJq28cKNbjV7Qx8UAAAzISURBVCwgFdHj+tbis98r1otX3+lplWTMePrybgmtpRtKveTZonRcc/qSt/DNQjglqyo/1G4KFUNkQony8mSm3MkVBKvxZnSA79EWg/mu97c1tWSamjIrkYWWrfORhWdkXDEa3Vqf37qdUzQYja6DSwb0LMWpF38OaapspWkoR1vlNf2GzMw3tRKzk3FZa0EubdXSfWhW2mwBpP/GgbOW3g0vzmqeVOxo6/c0NXWI4zcXIvOe9cUIVrnzY1tb461j8kwUGmjP5XGCN74My+SJw7WcGrHt+QxcWVZGFxjKqcU8dUi3c0qMM9hlGXU2RtFLMeigrFlpkSJTMtagWgkvKp404xLbOmCgqe1Uz8Lm8iaZNKvfGmslPe426Y2kWy73jBG8MTG41LqOlQxd26kR1Z/S6a1wgokfdHeiF/GdRWC8kGJmjWtnfHXYO+0FKdrEqq3KdfLy478KQYInnmpqGmjpIeuAI9H1y5JBvjFOfkJ1jkOGdL/lHkDOW0AOGnvBp3Q6AxXWtDtyoZReAGkx29cLQiAHyuog5WIwFcey8WGWCQcqa1CS/GwnGkHQ48q4mzLutqYOIDwL42qHG19YnJ/fHBtG/W2O90D38u3WzTxw5iMYd1db2Mq23ROJ5/U5CUNW4uu9xsXUrEy+PAn5lfmFhYX15aUCW+FOigQKRYwpAwPiAAxkSEcEjH+3hgekDveGxDjuEiEzsFzoEcfG8fIy5MKyWb4gIR2vuC8BNVVx7rNzA1YapbRM8jOdk8tbCxEySRs5v/7WdisA/NA51d3RJg6ImQ5xAAk3QRxr1eSNsbw0tOceG7stOxlOW3n1YoRkTU2lBoWDxQo1LnlyXi8MjY5irtrZSx6H8Mt6tVSIflnSCbE+MSyAofnZmYGmJhcitkmErnEVrnU84yGG6RpoVYPgEhvWP659sVIM6zMVCH2+qcnPpM968tFQcggzHTVvjp6fnzS93xtj7HZy3o0qDIht6GFgQERv0+EK6vprLbRkxsdvKz+g+iDlpSo9KmN3hA7Z08RCTMlyIbUGNEy7YGKTk8dpbDGue7KxUR1ziUYXWo0H9jhi9pS0szuUsgfUi3lUYVOHJ9OPhuqSIgLpgG+0GmVsGdUXk1Yd7BmhHC1iqVAoZF5JE1fm6HVH49sQ40r0dcQZP99zbf38vJwzL4vjhqATCIW0A/jsKbW2E7pRh239mf6M6D7VY+iDrW9sbm5iTBxbuVnIxry0zSL3n20JdzCK4eBDlFXahh3ym/aRsj1JkyvtnFRXE1M2OyLEBViIPCMxWuzZisxrh2jQTMpulJSWsLc1tbX1S49Ldq+0GtS3UL8wj7Gdl1657diKirqz8xlYVtrfKiEaD+Nx5qS9mEOaieo7o+XDBeLsl63zkWgr2UIQXVe3dzmYkN0siha9gx0dGZfHI3pEt+geV2SpPwjLSzlOiDltlMP5wqdGUBXy0phojSmNSpncYZiUTzrhpJ7dqY9iWYLI4k0XWfgTXVd/W6JB6ZOT/pQl53GdIoRu9FQ9yjKWHo61x2MBB1lrKi/5KSPc/XNItXtBLKx+7CnTKTUpzE01QuOZNtrDZtwLygr06A2lxgyXA6JtSH+Y63a5XB5R9ABPjDFg6EP78pRO/V4CH9AMK2XyqNnZZFIL+DohrRJmV7AHyt70hnIUu78cEBHJXeksIRRFANYmnSHnMGxG21/CsBjX2xUyehuHq5jUrVQ/LsQufyLxvDZEH70h/zZQQYWKEmUdipCP68fpHRAhldWOrcTGmOw0HPTpnkZzpQqHX4AxdXmo6mliFQntKTJ/Tgg9EKb3+UyFSvcKQEpXotlOGdDCYec1PaZj/LTHQwWxRSPckve1MBUB7aGY7GncUn118ISUkDe0LGRad2lArJtc0uahAjGGhf4B0LLSqDTCYasMiF2WDI4ogPt8akSllQo2a4GtZqeUMKwnNVPAMdIAgs2SykMG82dtcDdyi92OEJOJAASh6pMh9u7UiCqnMdiBMdhpwEhIs6Dl3p29RYACz+cAghmSg10eV1f/RBd6vNsQhsgMARa0+39qRJW5JxvPGd28KXujuUn18Xh1xY3gqQHMLDs6miTpgNtRhTH6jCixYrCQCXkB8+Udtaq6Ie5i/tAKRjs1T6fZ+OFOUhnWTc1g12trUqVtAJMwGJsny5Sljcmxqp7GbndQYsyx01aphOWeYxczpDHtNDK7EqENWmTR3Uy9Bf2ZJiOfi4gbWlY35xeIEuffslaLFnY/Zc/RO2/VXhJiV9QRQ+ajXWiHOFwIZgYUNslEMYmWxS32uDNjZCIi8scNpUoplzi9FNJaekiElB9YLbdJGSZDyIFuHhWvrSOTcWVQf6cUQA/A8vjYqa0FEjG+zNKVAVPeUOFAn0Na+V7xAm9X1BiS3LrNGxZyhWAw06HQDWTEfhepgdwanzi2Ira2ytOcGBTZcEVfw8Swkx4+IeXNQdZPnlPhjzOU1y9wBUDXIve9tqZMvwiZTFubap7EPnvGVjZbB2B5LCqPyNcvax9SCWBof57SudN7kSMHcqmUwJKNeXCmH2ty1TQHwd3f0TYwcMotG+gprPLGxNZxMiQ4vgzurQUyKLU4D0anrPBh+sO8QKtqfZKOekm7l+zatMdd0zaHLcyksOFY33gGBgY62hS/ksGaTiQdscOlCX4A4+Otg2OtY4PycO7YyjLKysr6FnB+Q/rg9zNCvhCvuVXbD1SUB0vMIciSCuNDu2l1qYb6aQTCccaeYjlpS0x3JoMhQVYd/ovKE0Ektomxz33qlKw/9C5sjHu22Zq53NrqEsnA5+b56OLCwkJ9JBJZ/BK4FKOIX8iKIFipXeSSz3tKpzfsT4X88VgYJWASsroBkVKstPYgv1TwdAeh+0z/QEeHmqqQbtcxMOARPR7sh/jdKY9HdZ6ngmjIVjLGMd46Dgi33EJGlRajksjzm8/6Czk+y/P4oeV5u0VetLXHJ9KllqSjT6pLMBjsH0CFSeaoKk0P55itiC60THQs/WikKp4L78nF5D8pwPimu4B0bvF267hh/f358/OXYX6LbDWMx7xkh0y1jrVrQpsFggOk2QOiSEyuijRVF+ndqDsXiKJH63zYR/mQ3io/3Ngic2CtLgyJZHaMTF9EogvrsDx/fvFL9VT+2haX7VCH/Bk1/ej3dJS2Hm0x4+53bcOHrxhwuT0tILo15blOYVWRDTvRI2p/L5DFcCJNZ7qCK2PoTRfnt8aXe8YXItF1/UyJfSBE+9H00zbY30ZSLE3cHnSVYqYyGlF7hjgXwB7odhkErTPLOElxYFy3SE4dlGY0W2+PLff0/L7g2tyaj6KVAnlE274ROgPigN7oAZCmC1ApGKndLdgDPa4StbZJ6QpKpgXDgsfjcZnllGSdTpouPczCZnXSqQKIyqTK+CbGRDKPu5I3Hhu694R0CozN97gV7aDL6BFdAwMmOCKZTH+/h4zOihJmxsxHPhRp1Lpis5xoqpiZtm4S2ZpHO12HYb/FuLxgLwmVYjJnssEO6EB/j26/PzOgBzqiNGKPaJCD+Cv5dwNGuFOK9nJCQGlW5SDmpCwCB3BrfWt+/RbAQyEsvXR/ntIpB3IHmKywoyeDhB1yhtIhORHXqX4SAlrcbqI0+VcDKpjuWxBviY1ZKMdzDqAgKXosJGQ5ISVtH6685KPGsyy2XT2icAbMhE0Gt6l6HDkEEo0SzUmGiemm261oTnEtohAnKZO6B6OkM5iSSafyreEAkXJLrO0sixryUgZMgE0ZT8XIR7KWDmKXstLcLbqDkVwLKz0FufbDC8ossZywxls9l9D/fEI5KqjqItMlPS2GrAx6FLy9aNY+EMa3JyTu8pRWwqK+0FmKbvUHEvdMo4lHkTBc0g8VQuJjlEigqYuURaAlnUi3xMUD6BL2sln7QOgoJRSbJGfiNrhJ9CqiKXPxIF4uhTm1UgccaUJbz0AJIbFJ3SxPeUjqIuqpC+l5OczJaOnE3r1u1j4QUtkzpo6XaSnJwdyGfJp0PMj5lWMlMRSXNauCi7fupFl7eCuLslmiJFx0iC6XrES3oQtKqCRV4wRphGGn2zOqHECxB0/i3O5WSn7ktBSMaVsH6LmYXi6cIh40n5UfxlIhP9rDVGsvszbVLFJgGHx3iafkREVVn5t4FcgL+jNYKuS4e5gu70N96LTkzmiEZImVqjx0MhIcWqbXQdu2u9fRJrTSXuhXtNimuEyM5dKwTT7rD5NNRE7TrqBvGiG+0ZsPkoqhbcANGY+kOMhxgl/KxdBpWw+yWftCSFNeDrr7+7uRrLCU5wV7LKD+gQNv1j4RUlRM4HnBzyiPrrLt8F7fBEIS49Aksey0WMx++dtDeESatYe3+v9b2VN21ZilNwAAAABJRU5ErkJggg=="
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Doraemon</h5>
                <p class="card-text">
                  Doraemon (Jepang: ドラえもん) adalah karakter fiksi dalam serial manga dan anime 
                  Jepang dengan nama yang sama yang dibuat oleh Fujiko F. Fujio, nama pena dari tim penulisan 
                  Hiroshi Fujimoto dan Motoo Abiko. Dia adalah sebuah robot kucing yang melakukan perjalanan waktu
                   dari abad ke-22 untuk menolong seorang anak laki-laki bernama Nobita Nobi.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/png;base64,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"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Dorami  </h5>
                <p class="card-text">
                  Dorami (Jepang:ド ラ ミ ど ら み Dorami) (lahir pada tanggal 2 Desember 2114) adalah adik perempuan 
                  Doraemon. Dia berwarna kuning, ekor bunga, bukan ekor rubah, 
                  dan memiliki pita merah besar, bukan telinga. Dia kebetulan sekitar 2 tahun lebih muda dari Doraemon. 
                  Anehnya, mereka adalah saudara kandung karena fakta bahwa mereka menggunakan jenis oli yang sama.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="https://www.monster-strike.com.tw/entryimages/0do1muriuhiu_12.png"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Suneo Hunekawa</h5>
                <p class="card-text">
                  Suneo Honekawa (骨川 スネ夫, Honekawa Suneo) adalah seorang anak orang kaya dari keluarga Honekawa,
                  akibatnya ia sering memamerkan barang miliknya pada teman-temannya, yang membuat teman-temannya menjadi 
                   iri.
                  Ia berpenampilan memilki wajah seperti rubah. Ia bercita-cita menjadi perancang busana terkenal.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="https://i.pinimg.com/236x/ff/0f/e9/ff0fe97f0cdf2dc63a12e5c4d9395920.jpg"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">Nobita Nobi</h5>
                <p class="card-text">
                  Nobita Nobi (野比のび太, Nobi Nobita) adalah tokoh protagonis utama dalam cerita Doraemon,
                  Ia adalah anak yang kurang beruntung sampai Doraemon datang dari abad ke-22 untuk membantunya, 
                  sehingga ia bisa memiliki masa depan yang lebih baik dalam kehidupannya nanti.[
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxITEhUTEhAWFhUXGRoXFxgXFxcYGB
                cYFRcYGBgXFRYaHSggGB4lHxUYIjEhJSkrLy4uFx8zODMtNygtLisBCgoKDg0OGhAQGy0mICU1KysrNTItLS0tLy03LS0tLS0rLS
                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"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">takeshi Gian Goda</h5>
                <p class="card-text">
                  Takeshi Goda (刚 田 武 Goda Takeshi), lahir tanggal 15 Juni 2001, biasanya dikenal dengan julukan
                   “Gian” (ジャイアン Jaian) sebuah kata dari bahasa Inggris “Giant” yang berarti raksasa, adalah anak 
                   pengganggu berbadan besar, kuat, dan cepat marah .
                </p>
              </div>
            </div>
        </div>
      </div>
    </div>
<!------------------------ Tentang -------------------------------------->
    
    <div class="container-fluid pt-5 pb-5">
      <div class="container">
        <h2 class="display-3 text-center" id="Tentang">Tentang </h2>
        <p class="text-center">
        CERITA DORAEMON
        </p>
        <div class="clearfix pt-5">
          <img
            src="https://asset-2.tstatic.net/jambi/foto/bank/images/doraemon-nobita-shizuka-suneo-dan-gian.jpg"
            class="col-md-6 float-md-end mb-3 crop-img"
            width="300"
            height="300"
          />
          <p>
            Doraemon adalah robot kucing dari abad ke-22 yang dikirim oleh cicit Nobita dari masa depan,
            Sewashi; ia memiliki "kantong ajaib" yang berisi alat-alat dari masa depan yang biasanya digunakan
             untuk membantu Nobita. Nobita sendiri merupakan seorang anak sekolah dasar yang malas dan kurang pintar 
             meskipun berhati lembut.
          </p>
          <p>
            Beberapa nilai moral positif yang terdapat pada film kartun Doraemon, 
            antara lain: Kasih sayang, Tolong menolong, Kerja keras, Kontrol diri, Kepedulian. 
          </p>
          <P>
          Doraemon merupakan manga populer yang dikarang oleh Fujiko F. Fujio sejak tahun 1969
          </P>
          <p>
            Doraemon berusaha memasukkan nilai-nilai anti-kekerasan, non-erotis, 
            perlindungan lingkungan hidup, integritas, keberanian, kekeluargaan, kehormatan, dan kegigihan.
          </p>
        </div>
      </div>
    </div>
 <!------------------------- tim ------------------------------->
    <div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="About Us">About Us</h2>
        <p>
         Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illo, rerum exercitationem iste eius nobis quos, rem 
         consequatur et reprehenderit in natus. Ad deserunt itaque, doloremque repellendus ducimus ipsa qui magni.
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4 text-center tim">
            <img
              src="https://cdn.gramedia.com/uploads/authors/Fujiko_F._Fujio_EHskHPX.jpg"
              class="rounded-circle mb-3"
            />
            <h4> Fujiko F. Fujio</h4>
            <p>karang/Pencipta </p>
            <p>tahun 1969</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-instagram"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoOm1xjmMwOht_I3zJZRwjRkMW4RHnyerd_g&s"
            />
            <h4>Hiroshi Fujimoto dan Motoo Abiko</h4>
            <p>Penulis</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-instagram"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="https://w7.pngwing.com/pngs/171/327/png-transparent-doraemon-desktop-doraemon.png"
              class="rounded-circle mb-3"
            />
            <h4>Doraemon </h4>
            <p> Peran utama </p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="https://www.youtube.com/watch?v=c2_ZGNLILgo" class="social"><i class="fa-brands fa-youtube"></i></a>
            </p>
        </div>
        </div>
      </div>
    </div>
 <!------------------------ Client ----------------------------------------->
    <div class="container-fluid client pt-5 pb-5">
      <div class="container text-center">
        <div class="row pt-4 gx-4 gy-4">
          <div class="col">
            <img
              src="https://cdn.iconscout.com/icon/free/png-256/microsoft-28-761688.png"
            />
          </div>
          <div class="col">
            <img
              src="https://cdn3.iconfinder.com/data/icons/glypho-social-and-other-logos/64/logo-facebook-512.png"
            />
          </div>
          <div class="col">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKuiiyRvMNxSMfZYNb5_b-GkEAAmiJkX071g&s" />
          </div>
          <div class="col">
            <img
              src="https://i.pinimg.com/originals/20/1d/17/201d17590b3a7bc8939ca37e577bbbd8.png"
            />
          </div>
          <div class="col">
            <img
              src="https://www.ictmagazine.nl/wp-content/uploads/2020/10/ibm-720x340-1.png"
            />
          </div>
        </div>
      </div>
    </div>
 <!-------------- kontak ------------------------->
    <div class="container-fluid pt-5 pb-5 kontak">
      <div class="container">
        <h2 class="display-3 text-center" id="Kontak Kami">Kontak Kami</h2>
        <p class="text-center">
          Thank you for visiting our website. Let me know if you have
          something to say
        </p>
        <div class="row pb-3">
          <div class="col-md-6">
            <input 
              class="form-control form-control-lg mb-3"
              type="text"
              id="Name"
              placeholder="Name"
              required
            />
            <input
              class="form-control form-control-lg mb-3"
              type="email"
              id="Email"
              placeholder="Email id"
              required
            />
            <input
              class="form-control form-control-lg"
              type="number"
              id="No. Phone"
              placeholder="No. Phone"
              required
            />
          </div>
          <div class="col-md-6">
            <textarea class="form-control form-control-lg" rows="5"></textarea>
          </div>
        </div>
        <div class="col-md-3 mx-auto text-center">
        
          <button type="submit" class="btn btn-danger btn-lg">
            Submit
          </button>
        </div>
      </div>
    </div>
<!-----------Footer ---------------------->
    <div class="container text-center pt-5 pb-5">
      PUTRI YANTI &copy; 2024
    </div>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
      crossorigin="anonymous"
    ></script>
  </from>
  </body>
</html>
    
