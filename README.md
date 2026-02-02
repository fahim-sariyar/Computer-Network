OSI মডেল হলো একটি স্ট্যান্ডার্ড নেটওয়ার্ক প্রোটোকল মডেল, যা কম্পিউটার নেটওয়ার্কে ডেটা কীভাবে এক ডিভাইস থেকে অন্য ডিভাইসে আদান-প্রদান হয় তা বোঝার জন্য ব্যবহৃত হয়।
এই মডেলে সম্পূর্ণ কমিউনিকেশন প্রক্রিয়াকে ৭টি পৃথক লেয়ারে ভাগ করা হয়েছে।

OSI মডেলের ৭টি লেয়ার

1️⃣ Physical Layer (Layer 1)

এই লেয়ারটি নেটওয়ার্কের ফিজিক্যাল উপাদান যেমন কেবল, কানেক্টর, হাব, সুইচ ইত্যাদি নিয়ন্ত্রণ করে।
ডেটা এখানে বাইনারি (0 ও 1) আকারে ট্রান্সমিট হয়।

উদাহরণ: Ethernet cable, Fiber optic, Voltage level

2️⃣ Data Link Layer (Layer 2)

এই লেয়ারটি ডেটাকে ফ্রেমে (Frame) রূপান্তর করে এবং
Error Detection ও Correction পরিচালনা করে।
এখানে ডিভাইস শনাক্ত করতে MAC Address ব্যবহার করা হয়।

উদাহরণ: Switch, MAC address, ARP

3️⃣ Network Layer (Layer 3)

এই লেয়ারের মূল কাজ হলো Routing।
ডেটাকে Packet আকারে গন্তব্য নেটওয়ার্কে পাঠানো হয় এবং
এখানে IP Address ব্যবহৃত হয়।

উদাহরণ: Router, IP, ICMP

4️⃣ Transport Layer (Layer 4)

এই লেয়ারটি ডেটাকে Segment এ ভাগ করে এবং নির্ভরযোগ্য ডেলিভারি নিশ্চিত করে।
এটি দুই ধরনের কমিউনিকেশন ব্যবহার করে:

TCP (Connection-oriented)

UDP (Connectionless)

উদাহরণ: TCP, UDP, Port Number

5️⃣ Session Layer (Layer 5)

এই লেয়ারটি দুটি ডিভাইসের মধ্যে Session তৈরি, পরিচালনা ও শেষ করে।
ডেটা স্ট্রিমের Synchronization নিশ্চিত করে।

উদাহরণ: Session establishment, Checkpoint

6️⃣ Presentation Layer (Layer 6)

এই লেয়ারটি ডেটাকে Compatible format এ রূপান্তর করে যাতে রিসিভার বুঝতে পারে।
এখানে:

Encryption

Decryption

Compression

কাজ করে।

উদাহরণ: SSL, TLS, Data format (JPEG, MP3)

7️⃣ Application Layer (Layer 7)

এটি OSI মডেলের সর্বশেষ ও সবচেয়ে কাছের লেয়ার যেখানে ব্যবহারকারী সরাসরি কাজ করে।
এই লেয়ারটি অ্যাপ্লিকেশন ও নেটওয়ার্কের মধ্যে সংযোগ তৈরি করে।

উদাহরণ: Web Browser, Email Client, HTTP, FTP, SMTP

OSI Model এর কাজের একটি উদাহরণ

ধরা যাক, আপনি একটি মেসেজ পাঠাচ্ছেন—

Application Layer: মেসেজটি অ্যাপ্লিকেশন দ্বারা তৈরি হয়

Presentation Layer: মেসেজ এনক্রিপ্ট বা কমপ্রেস হয়

Session Layer: কমিউনিকেশন সেশন চালু হয়

Transport Layer: ডেটা সেগমেন্টে ভাগ হয় (TCP/UDP)

Network Layer: IP Address ব্যবহার করে রাউটিং হয়

Data Link Layer: MAC Address দিয়ে ফ্রেম তৈরি হয়

Physical Layer: ডেটা বাইনারি আকারে ট্রান্সমিট হয়


OSI মডেল নেটওয়ার্ক কমিউনিকেশন বোঝার জন্য অত্যন্ত গুরুত্বপূর্ণ।
এটি ডেটা ট্রান্সমিশন প্রক্রিয়াকে ধাপে ধাপে ব্যাখ্যা করে এবং
নেটওয়ার্ক ডিজাইন, ট্রাবলশুটিং ও শেখার জন্য একটি আদর্শ কাঠামো প্রদান করে।
