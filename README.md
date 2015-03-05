# DBAuthCurl
DBOwner封装了对oauth2.0的简易封装。此类只是对curl的简易封装，方便开发者使用，开发者直接下载下来就可以使用。

include("/DBAuthCurl.php");
$dbAuthCurl = DBAuthCurl::dbGet($curl, $method, $parameters);
