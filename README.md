# libuseragent

## Build command:
  - ./configure && make && sudo make install
  
## Sample Usage:

```c++
  static const std::string regex_file = "/usr/local/share/uap/regexes.yaml";
  const UserAgentParser parser(regex_file);
  const auto uagent = parser.parse(
				   "Mozilla/5.0 (iPhone; CPU iPhone OS 5_1_1 like Mac OS X) AppleWebKit/534.46 "
				   "(KHTML, like Gecko) Version/5.1 Mobile/9B206 Safari/7534.48.3");
  std::cout<<uagent.os.family<<std::endl;
```
