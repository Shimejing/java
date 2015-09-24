# java
just for study.
==================
javac Hello.java
java Hello
=================
什么样的contributions会被github计算在内？
在热衷于在Github上刷contributions的人（比如我）看来，每周看着contributions涨涨涨，看着Contributions Calendar越来越绿意盎然，心里一股幸福感油然而生。

当然，这种心理现象就像LOL玩家喜欢看排名和胜盘一样，是病，得治。

有些时候，这些平凡而坚定的人，这些脱离了低级趣味的人，这些将有限的一生奉献到无限的为人类的爱与和平打代码的事业的人……惊奇地发现，自己push的commit没有被算入contributions里。或者自己赶在截止时间之前，辛辛苦苦地完成一个commit，结果发现算到新的一天里，然后苦心策划的连击就这样前功尽废了。这时候，so sad, so painful。

这种情绪是不好的，因为它意味着原本坚持打代码的朴素愿望已然变质，被外部化成为contributions的增加而打代码，失去了打代码的本意……不过要是没有这种contributions作为一种满足收集癖的动力，恐怕连坚持打代码的原本的朴素愿望也不会产生呢。这么说来真是说不清啊。好吧，让我们跳过纯粹道德批判，来看看主题：什么样的contributions会被Github计算在内？

为了弄清楚这个问题，避免悲剧的一再重演，我决定查看Github的相关政策法规，并且整理整理。现在就跟大家分享一下。

并非所有的contributions是生而平等的

正如人们所熟知，人生而不平等，同样的道理可以应用在contributions上。至少在Github上，有些contributions就是那么不幸。

contributions的创建时机

一个contributions被创建，需要满足“新建一个issue” || “发出一个pull request” || “创建一个commit”。

然而，如果一个contributions是通过创建commit来产生的，那么它就会面临生来的不平等。

尤其当你是一个commit contributions

commit contributions分为两种：

向一个不是你fork的版本库commit
向一个你fork的版本库commit
对于前者，必须是在默认的分支（一般为master）或者在gh-pages（就是当你直接在github上edit的时候创建的）分支上的commit才算数。

对于后者，要等到上游的人把代码merge到上游的默认的分支，你的commit才会被计算。如果你的comit没有被merge，那么自然就不会算数了。

当然还有些情况下不会计算到你的contributions里面的，比如你的commit记录是一年多以前的，或者那个commit的创建者没有跟你的Github帐号联系起来，等等。

BTW，对私有仓库的commit也是会被考虑在内的。具体的处理方式应该跟公有仓库是一样的。
