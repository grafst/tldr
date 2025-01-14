# a2ping

> छवियों को EPS या PDF फाइलों में परिवर्तित करें।
> अधिक जानकारी: <https://manned.org/a2ping>.

- एक छवि को PDF में बदलें (ध्यान दें: आउटपुट फ़ाइल नाम निर्दिष्ट करना वैकल्पिक है):

`a2ping {{छवि.ext/का/पथ}} {{आउटपुट.pdf/का/पथ}}`

- निर्दिष्ट विधि का उपयोग करके दस्तावेज़ को संपीड़ित करें:

`a2ping --nocompress {{none|zip|best|flate}} {{फ़ाइल/का/पथ}}`

- यदि मौजूद है तो HiResBoundingBox को स्कैन करें (ध्यान दें: यह डिफ़ॉल्ट रूप से हाँ है):

`a2ping --nohires {{फ़ाइल/का/पथ}}`

- मूल पृष्ठ के नीचे और बाईं ओर पृष्ठ सामग्री की अनुमति दें (नोट: यह डिफ़ॉल्ट रूप से नहीं है):

`a2ping --below {{फ़ाइल/का/पथ}}`

- `gs` के लिए अतिरिक्त तर्क पारित करें:

`a2ping --gsextra {{तर्क}} {{फ़ाइल/का/पथ}}`

- बाहरी प्रोग्राम में अतिरिक्त तर्क पास करें (यानी pdftops):

`a2ping --extra {{तर्क}} {{फ़ाइल/का/पथ}}`

- सहायता प्रदर्शित करें:

`a2ping -h`
