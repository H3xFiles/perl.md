# Perl Notes

``` perl
#!/user/bin/perl
```
## from shell
```perl
perl -e '<script>'
```
## variables
```perl
$s = "string";
$n = 3;
@arr = (1,2,3); $arr[1]
%list = (1, 'joe', 2 'lisa'); $list{3} = 'Marek'
```
## private - public variables
```perl
my $i;
local $e;
local FILE;
```
## open file
```perl
use strict;
use warnings;
 
my $filename = 'data.txt';
open(my $fh, '<:encoding(UTF-8)', $filename)
  or die "Could not open file '$filename' $!";
 
while (my $row = <$fh>) {
  chomp $row;
  print "$row\n";
}
```

```perl

```

```perl

```

```perl

```
