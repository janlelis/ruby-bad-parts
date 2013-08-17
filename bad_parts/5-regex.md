!SLIDE

    @@@ruby
    >> a = "Eurucamp #\n"
    >> a.gsub /#$/, ''
    # => ?

!SLIDE

    @@@ruby
    >> a = "Eurucamp #\n"
    >> a.gsub /#$/, ''
    # unterminated regexp meets end of file

!SLIDE

    @@@ruby
    >> a = "Eurucamp #\n"
    >> a.gsub /#$//, ''
    # => "Eurucamp #"
