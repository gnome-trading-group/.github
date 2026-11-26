<!-- you looked. most don't. the rest of it is at gnometrading.group, behind `ls -a`. -->

<div align="center">

```
   ▄▄▄▄   ▄▄▄▄▄▄  ▄▄▄▄
  ██      ▀▀██▀▀  ██ ▀▀
  ██ ▄▄▄    ██    ██ ▄▄▄
  ▀█▄▄█▀    ██    ▀█▄▄█▀
```

**Gnome Trading Group**

Electronic trading: market making and liquidity taking.<br>
Digital assets · prediction markets · equities · options

[gnometrading.group](https://gnometrading.group) · `contact@gnometrading.group`

</div>

<br>

```console
guest@gnome:~$ cat workshop/README.md
```

```
                   ┌──────────────────────────────────┐
   venues ═══ws═══▶│ SHARDS    collect · build books  │ ──▶ minute files
                   └──────────────────────────────────┘
                                    │ multicast
                                    ▼
                   ┌──────────────────────────────────┐
                   │ SESSION   strategy · OMS ·       │ ──▶ journal
                   │           risk · journal         │
                   └──────────────────────────────────┘
                                    │ orders / reports
                                    ▼
                   ┌──────────────────────────────────┐
   venues ◀══api═══│ GATEWAYS  sign · pace · track    │
                   └──────────────────────────────────┘
```

```console
guest@gnome:~$ grep -h '' workshop/*.md | shuf -n 5
```

> **Strategies never send orders.** They publish an intent. Something else decides how to get there.
>
> **One counter.** Every tick, intent, order and fill in a session takes the next number. "What happened first?" has an answer.
>
> **Nothing allocates.** The hot path is zero-garbage, and the build fails if that stops being true.
>
> **Failing closed.** When something is uncertain, the system stops trading. Making the money back doesn't lift the halt.
>
> **Same code, four places.** Research, backtest, paper and live run the identical runtime. Only the data and the fills change.

<sub>The full notes live on the website. They aren't linked. You'll find them.</sub>

<br>

```console
guest@gnome:~$ cat careers.md
```

A small team where everyone owns systems end to end, from research to production.

- You'd write the strategy, the risk check that stops it, and the dashboard that shows why.
- Latency is measured, not guessed. So are fills.
- Production code is the backtest code.

If that sounds like your kind of problem: `contact@gnometrading.group`

<br>

```console
guest@gnome:~$ ls repos/
ls: cannot open directory 'repos/': Permission denied

guest@gnome:~$ sudo !!
guest is not in the sudoers file. This incident will be reported to the head gnome.

guest@gnome:~$ █
```

<div align="center">
<sub><a href="https://gnometrading.group">gnometrading.group</a> · some things here are hidden.</sub>
</div>
