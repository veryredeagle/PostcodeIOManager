# PostcodeIOManager
Simple Java project to fetch data from postcodes.io


Example:

To get postcode from location:

String postcode = PostcodeIOManager.getNearestPostcode(51.5000743,-0.1483633);

To validate postcode:

bool isReal = PostcodeIOManager.validatePostcode("SL135WY");

To get all postcode details:

ArrayList<String> allDetails = PostcodeIOManager.getPostcodeDetails("SL135WY");

