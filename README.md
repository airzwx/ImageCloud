ImageCloud
==========

[vanillaforums plugin] lightweight image uploader using Qiniu Cloud as storage

To use this plugin, you need to modify your conf/config.php and add following items between two dividing lines and edit it according to your own information:

======dividing line======

$Configuration['Plugins']['ImageCloud']['Driver'] = 'Qiniu';

$Configuration['Plugins']['ImageCloud']['Qiniu']['AccessKey'] = 'YOUR_APP_ACCESS_KEY';

$Configuration['Plugins']['ImageCloud']['Qiniu']['SecretKey'] = 'YOUR_APP_SECRET_KEY';

$Configuration['Plugins']['ImageCloud']['Qiniu']['Bucket'] = 'YOUR_BUCKET_NAME';

$Configuration['Plugins']['ImageCloud']['Qiniu']['CloudURL'] = 'THE_DOMAIN_OF_THE_BUCKET_WITHOUT_http://_OR_/';

======dividing line======

An example for CloudURL:

$Configuration['Plugins']['ImageCloud']['Qiniu']['CloudURL'] = '9vamyp.com0.z5.glb.clouddn.com';
