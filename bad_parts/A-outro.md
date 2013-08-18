!SLIDE

## Nevertheless, we all know...

!SLIDE small-code

## Ruby is Beautiful

    @@@ruby
    # Calculate SHA-256 of STDIN
    q,z=[3,2].map{|t|i=l=1;(2..330).select{i-1<(l*=i)%i+=1}.map{|e|
    (e**t**-1*X=2**32).to_i&X-=1}}
    s=proc{|n,*m|a=0
    m.map{|e|a^=n>>e|n<<32-e}
    a}
    (gets(p)+'\x80'+"\x00"*((55-w=$_.size)%64)+[w*8].pack('Q').reverse).
    gsub(/.{64}/m){w=$&.unpack'N*'
    y=z
    64.times{|i|i>15&&w[i]=w[i-16]+(s[v=w[i-15],7,18]^v>>3)+
    w[i-7]+(s[w[i-2],17,19]^w[i-2]>>10)&X
    f=y[7]+s[u=y[4],6,11,25]+(u&y[5]^~u&y[6])+q[i]+w[i]
    y=[f+s[y[0],2,13,22]+(y[0]&y[1]^y[0]&y[2]^y[1]&y[2])&X]+y
    y[4]=y[4]+f&X}
    z=z.zip(y).map{|a,b|a+b&X}}
    puts'%.8x'*8%z

!SLIDE

# Keep Using Ruby!
## Slides at <a href="http://is.gd/ruby_bad_parts">is.gd/ruby_bad_parts</a>

CC-BY Jan Lelis
