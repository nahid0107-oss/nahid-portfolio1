# Nahid Hossain Portfolio — GitHub Pages (স্ট্যাটিক)

## লাইভ করার নিয়ম (১ মিনিট)
1. github.com এ নতুন Public repository খুলুন (যেমন `portfolio`)।
2. **Add file → Upload files** → এই জিপ আনজিপ করে ভেতরের **সব ফাইল ও assets ফোল্ডার** ড্র্যাগ করুন (`.nojekyll` সহ) → **Commit changes**।
3. **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**।
4. ১–২ মিনিট পর `https://USERNAME.github.io/portfolio/` লাইভ।

## এডমিন
- ঠিকানা: `সাইট/admin.html` — ID: `MDNAHID999`, Password: `052798`
- প্রথম লগইনেই নতুন ID ও ১২+ অক্ষরের পাসওয়ার্ড দিতে বাধ্য করবে।
- এডিট করে **Publish ট্যাব → Download data.js** → GitHub এ `data.js` রিপ্লেস করে Commit করলে সাইটে পরিবর্তন লাইভ হবে।
- **ভুলে গেলে:** `data.js` এর `"auth": {...}` অংশ মুছে এই অংশ বসান (পাসওয়ার্ড আবার 052798):
  `"auth": {"user": "MDNAHID999", "salt": "0vOpJoejiE3vACJrKUokjA==", "hash": "uzAx1kNXgZvij7+xqtcgepGJw3HPBeqsrKdctK2m++8=", "iter": 200000, "must": true}`

## ভিডিও লিংক
প্রজেক্টে "Video link" ঘরে YouTube / Facebook (পাবলিক) / Vimeo লিংক বা `.mp4` ফাইলের পথ দিন। YouTube থাম্বনেইল নিজে থেকে আসে।

## সীমাবদ্ধতা (সৎভাবে)
- GitHub Pages-এ সার্ভার নেই, তাই PHP/ডেটাবেস নেই। কন্টাক্ট ফর্ম ইমেইল অ্যাপ খুলবে (Site text-এ email দিন) অথবা Formspree endpoint দিলে সরাসরি ইনবক্সে যাবে।
- এডমিন পাসওয়ার্ড শুধু এডিটর খোলা আটকায়; সাইটের আসল সুরক্ষা হলো GitHub অ্যাকাউন্ট (শুধু আপনিই data.js বদলাতে পারেন)। GitHub এ 2FA চালু রাখুন।
- ভিজিটরের রিভিউ সরাসরি সাইটে বসে না; ইমেইলে আসে, আপনি Reviews ট্যাবে যোগ করবেন।
