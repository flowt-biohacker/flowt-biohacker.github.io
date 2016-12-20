.. title: Configuring Android Galaxy S6 on telcomsel's Mobile Data Network
.. slug: configuring-android-galaxy-s6-on-telcomsels-mobile-data-network
.. date: 2016-12-01 20:10:36 UTC+07:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

    One of the modern pleasures of traveling in South East Asia is ubiquitous 3 or 4G mobile data access. My experiences in Thailand and Malaysia have been phenomenal in this regard, as I can take care or hotel booking, directions, or language translation on the fly with little to no planning required. In Bali though, I ran into some difficulty. After negotiating the price for a new sim card and 6GB data plan down to a reasonable 125,000 IDR with a local vendor, I popped it in only to find that while calling and SMS functioned, I had no internet access to speak of! Unfortunately, this particular vendor wasn't the most honest of businessmen, and had little sympathy for my technical difficulties. Fortunately, after about an hour of research and fiddling, I found that the automatic APN configuration failed, and I simply had to perform it manually. 

    The correct APN settings were found here: http://www.telkomsel.com/services/basic-services/3062-GPRS, note that unless you can read Bahasa, google translate will come in useful on the linked page! In summary though, I simply had to create a new APN with 'name' = 'internet' and 'apn' = 'internet'. After that, I was in business! It seemed that my device did automatically register with the tecomsel server, though if yours does not you may need to text 'internet' to the number '5432' on indicated on the linked page.
