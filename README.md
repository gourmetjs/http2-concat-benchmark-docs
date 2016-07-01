This is repo contains images and tables used in [this article](http://gourmetjs.com/blog/http2/2016/05/30/http2-bundling.html).

## HTTP/2 Results

#### Between San Jose and US West (N. California)

 # |    1000 |      50 |       6 |       1 |
--:|--------:|--------:|--------:|--------:|
 1 | 1,462ms |   437ms |   460ms |   447ms |
 2 | 1,477ms |   502ms |   527ms |   509ms |
 3 | 1,457ms |   442ms |   413ms |   410ms |
 4 | 1,423ms |   452ms |   456ms |   458ms |
 5 | 1,391ms |   418ms |   410ms |   434ms |
 6 | 1,398ms |   438ms |   429ms |   584ms |
 7 | 1,382ms |   460ms |   565ms |   527ms |
 8 | 1,442ms |   775ms |   452ms |   504ms |
 9 | 1,442ms |   746ms |   493ms |   590ms |
10 | 1,407ms |   444ms |   462ms |   427ms |

![US West (N. California)](https://github.com/gourmetjs/http2-concat-benchmark-docs/blob/master/images/n_california.png)

#### Between San Jose and US East (N. Virginia)

 # |    1000 |      50 |       6 |       1 |
--:|--------:|--------:|--------:|--------:|
 1 | 1,588ms |   859ms |   930ms | 1,018ms |
 2 | 1,771ms | 1,239ms | 1,653ms | 1,628ms |
 3 | 2,901ms | 2,213ms | 1,721ms | 2,016ms |
 4 | 3,003ms | 2,567ms | 2,583ms | 2,367ms |
 5 | 3,786ms | 2,194ms | 1,951ms | 1,874ms |
 6 | 2,379ms | 1,535ms | 1,624ms | 1,528ms |
 7 | 2,718ms | 1,878ms | 1,783ms | 2,389ms |
 8 | 2,730ms | 1,637ms | 1,367ms | 1,489ms |
 9 | 2,169ms | 1,404ms | 1,917ms | 2,159ms |
10 | 3,395ms | 4,072ms | 2,317ms | 3,095ms |

![US East (N. Virginia)](https://github.com/gourmetjs/http2-concat-benchmark-docs/blob/master/images/n_virginia.png)

#### Between San Jose and Asia Pacific (Seoul)

 # |    1000 |      50 |       6 |       1 |
--:|--------:|--------:|--------:|--------:|
 1 | 3,262ms | 2,472ms | 2,857ms | 4,320ms |
 2 | 4,119ms | 2,889ms | 3,082ms | 3,152ms |
 3 | 4,102ms | 3,623ms | 3,290ms | 3,405ms |
 4 | 4,513ms | 3,142ms | 3,212ms | 3,025ms |
 5 | 5,612ms | 6,393ms | 5,383ms | 4,235ms |
 6 | 6,225ms | 3,672ms | 2,705ms | 2,575ms |
 7 | 4,890ms | 3,762ms | 4,087ms | 5,818ms |
 8 | 6,856ms | 4,119ms | 5,261ms | 4,556ms |
 9 | 5,771ms | 4,374ms | 1,898ms | 1,716ms |
10 | 2,531ms | 2,669ms | 2,351ms | 2,505ms |

![Asia Pacific (Seoul)](https://github.com/gourmetjs/http2-concat-benchmark-docs/blob/master/images/seoul.png)

## HTTP/1.1 Results

#### US West (N. California)

 # |    1000 |      50 |       6 |       1 |
--:|--------:|--------:|--------:|--------:|
 1 | 5,145ms |   548ms |   243ms |   267ms |
 2 | 5,514ms |   513ms |   239ms |   250ms |
 3 | 5,528ms |   526ms |   239ms |   288ms |
 4 | 5,715ms |   540ms |   273ms |   241ms |
 5 | 5,441ms |   469ms |   235ms |   259ms |

#### US East (N. Virginia)

 # |     1000 |      50 |       6 |       1 |
--:|---------:|--------:|--------:|--------:|
 1 | 16,733ms |   902ms |   455ms |   625ms |
 2 | 16,039ms |   899ms |   439ms |   898ms |
 3 | 16,456ms |   875ms |   442ms |   886ms |
 4 | 15,865ms |   756ms |   426ms |   894ms |
 5 | 16,367ms |   951ms |   436ms |   937ms |

#### Asia Pacific (Seoul)

 # |     1000 |      50 |       6 |       1 |
--:|---------:|--------:|--------:|--------:|
 1 | 27,539ms | 1,561ms |   700ms | 1,648ms |
 2 | 27,728ms | 1,571ms |   714ms |   994ms |
 3 | 27,557ms | 1,446ms |   768ms |   903ms |
 4 | 28,010ms | 1,483ms |   794ms | 2,322ms |
 5 | 27,814ms | 1,489ms |   693ms |   993ms |
