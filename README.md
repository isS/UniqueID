UniqueID
========

分布式下的PHP生成一个唯一id.

* $_SERVER['UNIQUE_ID'].
* 客户端ip.
* microtime().
* 0-999999的随机数


## About

* Author : Jianyi Shao
* Location : https://github.com/isS/UniqueID

## Example

    <?php

    include('libraries/UniqueID.php');

    $UniqueID = new UniqueID;

    $uid = $UniqueID->get();

    ?>
