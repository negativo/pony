我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# 🐴 `PONY` 🌈

Make rainbow text !!

<img src="https://i.imgur.com/pDbvLG0.gif" height=40>

## Getting Started

### Installing

To start using Pony, install Go and run `go get`:

```sh
$ go get -u github.com/tidwall/pony
```

This will retrieve the library.

### Usage

There's only the one function:

```go
func Text(phrase string, offset int) string
```

Here're two examples for the price of one.

```go
package main

import (
	"fmt"
	"strings"
	"time"

	"github.com/tidwall/pony"
)

func main() {
	// Create a single line of dashes that are VERY wonderful to gaze upon.
	fmt.Printf("%s\n", pony.Text(strings.Repeat("-", 80), 0))
	
	// Create a rainbow effect that will straight up dazzle!
	for i := 0; ; i++ {
		fmt.Printf("\r%s ",
			pony.Text("Mute - thy coronation - Meek - my Vive le roi", i),
		)
		time.Sleep(time.Second / 15)
	}
}
```




## Contact

Josh Baker [@tidwall](http://twitter.com/tidwall)

## License

Pony source code is available under the MIT [License](/LICENSE).

