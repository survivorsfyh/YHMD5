# YHMD5

算法原理

对MD5算法简要的叙述可以为:
MD5以512位分组来处理输入的信息,且每一分组又被划分为16个32位子分组;
经过了一系列处理后,算法的输出由四个32位分组组成,将这四个32位分组级联后将生成一个128位散列值.

使用

[string md5String];

[string sha1String];

[string sha256String];

[string sha512String];

[string hmacSHA1StringWithKey:@""];
[string hmacSHA256StringWithKey:@""];
[string hmacSHA512StringWithKey:@""];
