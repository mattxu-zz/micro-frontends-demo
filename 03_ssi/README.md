# Server-side Integration with server side includes

Edge Side Includes (ESI) is a technology or a markup language used to assemble content at the edge layer, such as CDN.

<esi:include src="https://tractor.example/fragment" />

FALLBACKS
<esi:include
src="https://tractor.example/fragment"
alt="https://fallback.example/sorry" />

TIMEOUTS
<esi:include
src="https://tractor.example/fragment"
maxwait="500" />

Pros
- Can be written simply and has minimal features such as Fallback and Timeout
- ESI is unique in that you can take a flexible caching strategy where dynamic and static content live together.

Cons
- Local development can be tricky