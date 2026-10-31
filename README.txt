ANKIT VAYAM JAN SEVA KENDRA - READY CONFIG

index.html में Firebase और Supabase configuration पहले से भरी हुई है।
इसे HTTPS hosting पर अपलोड करें।

महत्वपूर्ण:
1. Firebase project: jan-seva-kendr-2
2. Admin email: ankitcps003@gmail.com
3. Admin का password Firebase और Supabase दोनों में एक जैसा होना चाहिए।
4. Supabase bucket का नाम janseva-private और Private होना चाहिए।
5. Supabase Authentication में Confirm email OFF होना चाहिए।
6. Firebase Firestore में वही Rules प्रकाशित होने चाहिए जो इस ऐप के users/{uid} और applications/{appId} schema से मेल खाते हैं।
7. Firebase Storage का उपयोग नहीं होता। Documents Supabase Storage में रखे जाते हैं।
8. Customer login मोबाइल नंबर + password से है; SMS OTP/फोन ownership verification नहीं है।
9. Supabase publishable key client-side इस्तेमाल के लिए है। कभी भी service_role/secret key वेबसाइट में न डालें।
10. असली ग्राहकों के दस्तावेज़ लेने से पहले dummy account और dummy PDF/JPG से पूरा परीक्षण करें।
