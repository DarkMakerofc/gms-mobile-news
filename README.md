<h2 align="center"> GMS MOBILE NEWS </h2>

<div id="logo" align= "center">
<a>
<object type="image/svg+xml" data="https://fdn.gsmarena.com/vv/assets12/i/logo.svg"><img src="https://fdn.gsmarena.com/vv/assets12/i/logo-fallback.gif" alt="GSMArena.com"></object>
</a>
</div>

<h4 align="center">

🗞️ This is UnOfficial Mobile News Information Web Scraper. Created By [Mr Nima](https://github.com/DarkMakerofc). <br>

 </h4>
 
 [ Using This Npm Package ]
* [Get All News](#allnews)
* [Get News Using Link](#latest)
* [Get Latest News](#fromlink)


<br>

#### ⬇️ Install Package 
     npm install gms-mobile-news
or 

     yarn add gms-mobile-news

<br>

#### ➡️ Require Package 
     const { GMSNEWS } = require('gms-mobile-news')

#### ▶️ Start Package 
     const news = await GMSNEWS()
     
     
#### 📝 Get All News List 

<a name= "allnews">

```
news.allnews()  
.then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });

```

#### ✅ All News Result 

```
{
   "creator": "MR NIMA",
   "status": true,
   "result": [
      {
         "title": "OnePlus Watch 2 with Wear OS to be unveiled at MWC next month",
         "link": "https://www.gsmarena.com/oneplus_watch_2_with_wear_os_to_be_unveiled_at_mwc_next_month-news-61302.php",
         "date": "20 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/oneplus-watch-2-mwc/-344x215/gsmarena_000.jpg",
         "shortDesc": "Last year we heard that the OnePlus Watch 2 would finally launch this year, and today a new rumor definitely corroborates that. According to a source that has been accurate at times in the past, the..."
      },
      {
         "title": "Google teases new Minty Fresh colorway for the Pixel 8 Pro",
         "link": "https://www.gsmarena.com/google_teases_new_minty_fresh_colorway_for_the_pixel_8_pro-news-61301.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/google-pixel-8-pro-new-color/-344x215/gsmarena_000.jpg",
         "shortDesc": "Google's online store is now teasing a new drop. It's not a new device, mind you, just a new color for the Pixel 8 Pro. It will become available on January 25 at midnight PT, and it's called Minty..."
      },
      {
         "title": "Apple Vision Pro pre-orders are live, Apple releases a 10-minute \"guided tour\" video for it",
         "link": "https://www.gsmarena.com/apple_vision_pro_preorders_are_live_you_wont_believe_whats_in_the_box-news-61300.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/apple-vision-pro-pre-orders-start/-344x215/gsmarena_000.jpg",
         "shortDesc": "Today Apple has started taking pre-orders for its first \"spatial computer\", the Vision Pro headset. It will become available, as previously announced, on February 2.\n\nWith the pre-order page come..."
      },
      {
         "title": "Samsung Galaxy A25 5G in for review",
         "link": "https://www.gsmarena.com/samsung_galaxy_a25_in_for_review-news-61293.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/samsung-galaxy-a25-ifr/-344x215/gsmarena_000.jpg",
         "shortDesc": "Say hello to the Samsung Galaxy A25 - the entry-level phone that is however very important for Samsung in its quest to regain the smartphone crown.\n\nThe Galaxy A25 needs to live up, or as the case..."
      },
      {
         "title": "vivo G2 announced with Dimensity 6020 and 5,000 mAh battery",
         "link": "https://www.gsmarena.com/vivo_g2_announced_with_dimensity_6020_and_5000_mah_battery-news-61291.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/vivo-g2-ofic/-344x215/gsmarena_000.jpg",
         "shortDesc": "Vivo G2 is the latest entry-level smartphone to launch in China. The device has a Dimensity 6020 chip, a 90Hz refresh rate screen and a 5,000 mAh battery with 15W charging. These specs align with the..."
      },
      {
         "title": "X brings audio and video calls to Android ",
         "link": "https://www.gsmarena.com/x_brings_audio_and_video_calls_to_android_-news-61290.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/x-voice-video-calls-android/-344x215/gsmarena_000.jpg",
         "shortDesc": "X (formerly Twitter) now supports voice and video calls on Android. The feature was already available for iOS users since October and is now coming to Android users. Just like on iOS, you’ll need an..."
      },
      {
         "title": "Huawei says about 5,000 native HarmonyOS apps coming this year",
         "link": "https://www.gsmarena.com/huawei_about_5000_native_harmonyos_apps_coming_this_year-news-61288.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/harmonyos-next-video-teaser/-344x215/gsmarena_000.jpg",
         "shortDesc": "During its HarmonyOS Ecosystem development event, Huawei's President of Device Cloud announced that the HarmonyOS NEXT software system marks the second stage of development. By the end of 2024, the..."
      },
      {
         "title": "Poco M6 in for review",
         "link": "https://www.gsmarena.com/poco_m6_in_for_review-news-61247.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/poco-m6-ifr/-344x215/gsmarena_000.jpg",
         "shortDesc": "A little late to the party but we finally have our hands on the India-exclusive Poco M6. The phone starts at just INR 9,999 ($120), which Poco claims makes it the most affordable 5G smartphone..."
      },
      {
         "title": "YouTube and Spotify will not offer native apps for Apple Vision Pro",
         "link": "https://www.gsmarena.com/youtube_and_spotify_will_not_offer_native_apps_for_apple_vision_pro-news-61285.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/23/06/hot-take-vision-pro/-344x215/gsmarena_000.jpg",
         "shortDesc": "Netflix app will not work on the upcoming Apple Vision Pro, and now Bloomberg reports YouTube and Spotify also have no plans on delivering apps for the augmented reality headset.\n\nNone of these..."
      },
      {
         "title": "iPhone 16 Capture button rumored to bring zoom control",
         "link": "https://www.gsmarena.com/iphone_16_capture_button_rumored_to_bring_zoom_control-news-61286.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/apple-capture-button-zoom-control-rumor/-344x215/gsmarena_000.jpg",
         "shortDesc": "Apple is rumored to bring a new Capture button on its iPhone 16 Pro and 16 Pro Max which we saw in leaked renders earlier this month. Now, The Information is reporting that Apple is testing the..."
      },
      {
         "title": "Canalys: Smartphone market in India rebounds in Q4, posts 20% YoY increase",
         "link": "https://www.gsmarena.com/canalys_smartphone_market_in_india_rebounds_in_q4_brings_yearly_shipment_drop_down_to_just_2-news-61284.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/23/12/samsung-galaxy-s23-fe-exynos-ifr/-344x215/gsmarena_000.jpg",
         "shortDesc": "Canalys revealed the smartphone market in India had a year-on-year growth for the first time in five quarters during Q4 2023. Vendors saw a 20% increase in shipments between October and December,..."
      },
      {
         "title": "Samsung Galaxy A13 4G receives Android 14-based One UI 6 update",
         "link": "https://www.gsmarena.com/samsung_galaxy_a13_4g_android_14_one_ui_6_update-news-61283.php",
         "date": "19 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/22/12/samsung-galaxy-a13-android-13-one-ui-5-update/-344x215/gsmarena_001.jpg",
         "shortDesc": "The Samsung Galaxy A13 5G received the Android 14-based One UI 6 update last month, which is now rolling out for the 4G version.\n\nThe One UI 6 update for the Samsung Galaxy A13 4G has firmware..."
      },
      {
         "title": "Xiaomi Mix Flip gets certified in China with support for satellite connectivity",
         "link": "https://www.gsmarena.com/xiaomi_mix_flip_gets_certified_in_china_with_support_for_satellite_connectivity-news-61282.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot//news/24/01/xiaomi-mix-flip-certified/-344x215/gsmarena_000.jpg",
         "shortDesc": "Back in September of last year we first heard that Xiaomi was working on a flip-style foldable to complement the Mix Fold line in its portfolio. This was to be called Xiaomi Mix Flip, and it was..."
      },
      {
         "title": "Samsung Galaxy AI is coming to these older devices",
         "link": "https://www.gsmarena.com/samsung_galaxy_ai_is_coming_to_these_older_devices-news-61281.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot//news/24/01/galaxy-ai-features-older-devices/-344x215/gsmarena_000.jpg",
         "shortDesc": "Yesterday, Samsung unveiled the Galaxy S24, Galaxy S24+, and Galaxy S24 Ultra - all three models bursting at the seams with AI. Galaxy AI, in fact. They will be running Android 14 of course, with One..."
      },
      {
         "title": "Tecno's foldable, the Phantom V2 Fold, pops up on Geekbench, revealing key specs",
         "link": "https://www.gsmarena.com/tecnos_foldable_the_phantom_v2_fold_pops_up_on_geekbench_revealing_key_specs-news-61280.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot//news/24/01/tecno-phantom-v2-fold-geekbench/-344x215/gsmarena_000.jpg",
         "shortDesc": "Tecno's second-generation foldable, the Phantom V2 Fold, is expected to arrive in Q1 this year and its likely debut is during this year's MWC 2024 in Barcelona. Ahead of the announcement, the handset..."
      },
      {
         "title": "HarmonyOS Next gets closer to prime time, video shows off the new UI design language",
         "link": "https://www.gsmarena.com/harmonyos_next_gets_closer_to_prime_time_video_shows_off_the_new_ui_design_language-news-61278.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/harmonyos-next-video-teaser/-344x215/gsmarena_000.jpg",
         "shortDesc": "HarmonyOS Next is getting closer to release – Huawei just posted an introduction video that highlights some of the changes to the UI design language. It’s trying to break away from the drab flat..."
      },
      {
         "title": "Samsung posts official hands-on videos detailing Galaxy S24 series’ AI features ",
         "link": "https://www.gsmarena.com/samsung_posts_official_handson_videos_detailing_galaxy_s24_series_ai_features_-news-61279.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot//news/24/01/samsung-galaxy-ai-hands-on-videos/-344x215/gsmarena_00.jpg",
         "shortDesc": "Samsung demoed a ton of new AI capabilities on stage at yesterday’s Galaxy Unpacked event as part of its Galaxy AI suite on the Galaxy S24 series. Samsung Newsroom now shared a series of videos..."
      },
      {
         "title": "Realme 12 Pro+ new color, more camera specs revealed",
         "link": "https://www.gsmarena.com/realme_12_pro_new_color_more_camera_specs_revealed-news-61277.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/realme-12-pro-new-color-camera-details/-344x215/gsmarena_001.jpg",
         "shortDesc": "Realme updated its landing page for the 12 Pro announcement on January 29, revealing one more color option of the upcoming phone.\n\nThe 12 Pro+ will have a cream version with golden trims around the..."
      },
      {
         "title": "The Galaxy S24 Ultra's 4K 120fps and 8K zoom video are a very big deal ",
         "link": "https://www.gsmarena.com/the_galaxy_s24_ultras_4k_120fps_and_8k_zoom_video_are_a_very_big_deal_-news-61276.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/samsung-galaxy-video/-344x215/gsmarena_000.jpg",
         "shortDesc": "There's a lot to uncover from Samsung's Galaxy S24 Ultra launch. The sensor sizes, the camera samples, and now some interesting camera details.\n\nThe Samsung Galaxy S24 Ultra is a surprisingly..."
      },
      {
         "title": "Samsung Galaxy A15 5G and Galaxy A25 5G debut in the US",
         "link": "https://www.gsmarena.com/samsung_galaxy_a15_5g_galaxy_a25_5g_usa_price_sale_date-news-61274.php",
         "date": "18 January 2024",
         "image": "https://fdn.gsmarena.com/imgroot/news/24/01/samsung-galaxy-a15-5g-a25-5g-usa-price-sale-date/-344x215/gsmarena_001.jpg",
         "shortDesc": "The Samsung Galaxy A15 5G and Galaxy A25 5G, unveiled last month, are now available in the US.\n\nThe Samsung Galaxy A15 5G comes in a single 8GB/128GB configuration with two color options - Blue..."
      }
   ]
}

```
</a>

<br>

<br>


#### 📝 Fetch Latest News

<a name= "latest">

```
news.latest_news()
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });

```

#### ✅ Latest News Result

```
{
   "creator": "MR NIMA",
   "status": true,
   "result": {
      "title": "Samsung Galaxy A25 5G in for review",
      "date": "19 January 2024",
      "link": "https://www.gsmarena.com/samsung_galaxy_a25_in_for_review-news-61293.php",
      "image": "https://fdn.gsmarena.com/imgroot/news/24/01/samsung-galaxy-a25-ifr/-952x498w6/gsmarena_000.jpg",
      "short_desc": "Say hello to the Samsung Galaxy A25 - the entry-level phone that is however very important for Samsung in its quest to regain the smartphone crown.\n\nThe Galaxy A25 needs to live up, or as the case...",
      "full_desc": "Say hello to the Samsung Galaxy A25 - the entry-level phone that is however very important for Samsung in its quest to regain the smartphone crown.\nThe Galaxy A25 needs to live up, or as the case may be, surpass its predecessor, the Galaxy A24 and we'd say it does it thoroughly.\nThe new phone adds 5G (the Galaxy A24 was LTE-only) courtesy of a more efficient 5nm Exynos 1280 chipset. It also brings the Super AMOLED screen to 120Hz, up from 90Hz on its predecessor. Sadly that AMOLED still lacks a fingerprint scanner embedded into it - it's a capacitive side-mounted one for the Galaxy A25.\nFinally, you get a higher-res 8MP ultrawide compared to a 5MP one on the outgoing model.\nThere's not much to say about the box contents. Like the A24, the Galaxy A25 ships with a single USB cable - if it's good enough for the Galaxy S24 Ultra, it's good enough for one of the cheapest Galaxy A members, we guess.\nWe got the Personality Yellow unit, an enchanting color. There's a more subdued Brave Black, Fantasy Blue, and an Optimistic Blue.\nThe Galaxy A25 adopts Samsung's updated design language with a slightly sculpted frame, which is both nicer to touch and more secure in the hand.\n\n\n\nThe Samsung Galaxy A25\nNow then, let's get to testing. Stay tuned for our findings!"
   }
}

```
</a>
<br>
<br>

#### 📝 Get News From Link

<a name= "fromlink">

```
news.fromlink("https://www.gsmarena.com/samsung_galaxy_a25_in_for_review-news-61293.php")
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });
```

#### ✅ Latest News Result

```
{
   "creator": "MR NIMA",
   "status": true,
   "result": {
      "title": "Samsung Galaxy A25 5G in for review",
      "date": "19 January 2024",
      "link": "https://www.gsmarena.com/samsung_galaxy_a25_in_for_review-news-61293.php",
      "image": "https://fdn.gsmarena.com/imgroot/news/24/01/samsung-galaxy-a25-ifr/-952x498w6/gsmarena_000.jpg",
      "short_desc": "A good step-up from the Galaxy A24. Say hello to the Samsung Galaxy A25 - the entry-level phone that is however very important for Samsung in its quest to...",
      "full_desc": "Say hello to the Samsung Galaxy A25 - the entry-level phone that is however very important for Samsung in its quest to regain the smartphone crown.\nThe Galaxy A25 needs to live up, or as the case may be, surpass its predecessor, the Galaxy A24 and we'd say it does it thoroughly.\nThe new phone adds 5G (the Galaxy A24 was LTE-only) courtesy of a more efficient 5nm Exynos 1280 chipset. It also brings the Super AMOLED screen to 120Hz, up from 90Hz on its predecessor. Sadly that AMOLED still lacks a fingerprint scanner embedded into it - it's a capacitive side-mounted one for the Galaxy A25.\nFinally, you get a higher-res 8MP ultrawide compared to a 5MP one on the outgoing model.\nThere's not much to say about the box contents. Like the A24, the Galaxy A25 ships with a single USB cable - if it's good enough for the Galaxy S24 Ultra, it's good enough for one of the cheapest Galaxy A members, we guess.\nWe got the Personality Yellow unit, an enchanting color. There's a more subdued Brave Black, Fantasy Blue, and an Optimistic Blue.\nThe Galaxy A25 adopts Samsung's updated design language with a slightly sculpted frame, which is both nicer to touch and more secure in the hand.\n\n\n\nThe Samsung Galaxy A25\nNow then, let's get to testing. Stay tuned for our findings!"
   }
}

```
</a>

# Author : [@mrnima](https://github.com/darkmakerofc)

All news rights belong to [www.gsmarena.com](https://www.gsmarena.com) site
