ফিসাবিলিল্লাহ ফাউন্ডেশন — PWA স্টার্টার

এটি একই ওয়েব অ্যাপকে অনলাইনে ব্যবহার এবং সমর্থিত Android ব্রাউজার থেকে হোম স্ক্রিনে ইনস্টল করার জন্য প্রস্তুত করা হয়েছে।

ফাইল:
- index.html: Splash, Login demo, Dashboard
- manifest.webmanifest: ইনস্টলযোগ্য অ্যাপের পরিচিতি
- sw.js: অফলাইন ক্যাশ
- icons/: অ্যাপ আইকন

অনলাইনে প্রকাশ:
1. GitHub-এ একটি নতুন Public repository তৈরি করুন।
2. এই ZIP-এর সব ফাইল ও icons ফোল্ডার repository-তে আপলোড করুন।
3. Settings > Pages > Deploy from a branch > main / root নির্বাচন করে Save করুন।
4. প্রকাশিত HTTPS লিংক মোবাইলের Chrome-এ খুলুন।

Android-এ ইনস্টল:
1. প্রকাশিত HTTPS লিংক Chrome-এ খুলুন।
2. Chrome-এর ⋮ মেনু > Install app অথবা Add to Home screen নির্বাচন করুন।
3. ইনস্টল হলে ফোনের অ্যাপ তালিকা/হোম স্ক্রিন থেকে খুলুন।

সীমাবদ্ধতা:
এটি এখনও UI/PWA প্রোটোটাইপ। লগইনটি ডেমো; কোনো বাস্তব ব্যবহারকারীর অ্যাকাউন্ট, ডেটাবেজ,
সদস্য/অনুদানের রেকর্ড বা নিরাপদ Super Admin/Treasurer permission নেই।
বাস্তব তথ্য দেওয়ার আগে Supabase/Firebase backend, authentication, access rules,
backup ও security testing যোগ করতে হবে। Public GitHub repository-তে গোপন তথ্য রাখবেন না।
