# naif

  naif is a framework to build dumb chat machines


```

channels        channel adapter              naif server     backends

                ┌─────────────────────┐      ┌────────┐
terminal   ───> │ terminal            │ ───> │ naif   │
           <─── │ adapter             │ <─── │ server │
                └─────────────────────┘      │        │      ┌──────────────┐
                                             │        │ ───> │ any service  │
                ┌─────────────────────┐      │        │ <─── │              │
e─mail     ───> │ e─mail              │ ───> │        │      └──────────────┘
           <─── │ adapter             │ <─── │        │
                └─────────────────────┘      │        │      ┌──────────────┐
                                             │        │ ───> │ database     │
                ┌─────────────────────┐      │        │ <─── │              │
(Telegram) ───> │ any (messaging)     │ ───> │        │      └──────────────┘
Messenger  <─── │ adapter             │ <─── │        │
                └─────────────────────┘      │        │      ┌──────────────┐
                                             │        │ ───> │ anything     │
                ┌─────────────────────┐      │        │ <─── │              │
Anything   ───> │ e─mail/webhooks/any │ ───> │        │      └──────────────┘
           <─── │ adapter             │ <─── │        │
                └─────────────────────┘      │        │
                                             │        │
                                             └────────┘

```

# Code ?

coming soon (December 2016)
