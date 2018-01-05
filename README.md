# TPE-AIUB
How to Give TPE easily

যে সাবজেক্টের TPE দিতে হবে, পোর্টালে সেই পেজে চলে যাই, তারপর google chrome browser হলে 
right বাটনে ক্লিক করে inspect (firefox হলে inspect element) সিলেক্ট করি, যে নতুন ভিউ 
টা আসবে অইখান থেকে console ট্যাবটা সিলেক্ট করে নীচের script টুক paste করি ।

# Script

(function(){ 
[].forEach.call( document.querySelectorAll('input[type="radio"][value="5"]'),function(rdo){rdo.checked = true} ); 
document.getElementById("Comment").value = "awesome"; document.forms[0].submit();})();

value="5" দিলে প্রথম টা সিলেক্ট হবে মানে "Strongly agree"
value = "4" দিলে "Agree" এইভাবে কমতে থাকবে আর 
Comment এর value change করতে "awesome" এর এইখানে নিজের ইচ্ছা মত দিতে হবে 
এরপর enter press করলে সাবমিট হয়ে যাবে, এভাবে সব TPE এর পেজে এইকাজ টুক করতে হবে।  :-)
