### The Name of _Nothing_

or perhaps

### _Nothing_ Has A Name

I [maybe 'Sandi'?] gave a talk at RailsConf called [_Nothing is Something_](http://confreaks.tv/videos/railsconf2015-nothing-is-something).

In this talk you'll notice that I am [cheerfully](httpSandi://www.youtube.com/watch?v=29MAL8pJImQ&feature=youtu.be&t=1417) [heckled](httpSandi://www.youtube.com/watch?v=29MAL8pJImQ&feature=youtu.be&t=1659) by Ryan Davis. He met me as I walked off stage and the following conversation ensued.

Ryan: Hey, Sandi...seems like you could clean that up with an identity object.

Sandi: Identity _object_? huh?

Ryan: Yes, an identity object, you know, like an identity function.

Sandi: Identity _function_? huh?

Ryan: You know... the functional equivalent of a no-op, like the additive identity or multiplicative identity.

Sandi: _Additive_ or _multiplicative_ identity? huh?


As you can see, Sandi is in a 'huh?' loop. At this point she prevails upon Ryan to schedule a call to chat about this concept of 'identity'.

Ryan: [I guessed what you'll say, but I yield]

It's all very simple.  
0 is the identity function for addition.  
1 is the identity function for multiplication.

Sandi:

Those words mean nothing. You are playing a cruel joke on me.

Ryan: [more detailed explanation]

Sandi: So, if I were to translate the words

> 0 is the identity function for addition

into code, it would look like:

<pre><code class="language-ruby">def add_to_zero(number)
  0 + number
end
</pre>

Are you saying the following implementation is equally correct?

<pre><code class="language-ruby">def add_to_zero(number)
  number
end
</pre>

Well, okay, I concede that the function returns the correct answer, but this is extremely confusing and seems completely pointless. How is this 'identity'? I'm clearly using a different definition for this word.

Ryan: yes, but that's the word _they_ use. You're stuck with it.

Ryan: [description of the concept of identities and different types]

Sandi: OK, I think I get identity values now, and the identity function. What's an identity object?

Ryan: [describe identity objects in context of house]

Sandi: [describe not liking 1 object duck typing to both]

Ryan: of course, that was arbitrary on my part and shouldn't matter.

Sandi: [describe not liking House::Identity being internal/bound to house]

Ryan: if it quacks correctly, it shouldn't matter where we put it.

["identity object" in pattern form ??]

So, to functional programmers and math-y types, the _nothing_ describe in _Nothing is Something_ is called Identity.
