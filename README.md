# Python-program-to-remove-leading-zeros-from-an-IP-address.
import re
ip = &quot;216.08.094.196&quot;
string = re.sub(&#39;\.[0]*&#39;, &#39;.&#39;, ip)
print(string)

Output:
216.8.94.196
