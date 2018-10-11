# rubytest

## Conver this
```
[host.example.com,[limits:[cpu:1 memory:2000Mi] requests:[cpu:600m memory:1200Mi]]]

to

{"host.example.com"=> {"limits" => { "cpu" => "1","memory"=>"2000Mi"},"requests" =>{"cpu"=>"600m","memory"=>"1200Mi"}}}
```
