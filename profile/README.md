<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alicelanguage/.github/main/assets/brand/alice-logo-dark.svg">
    <img src="https://raw.githubusercontent.com/alicelanguage/.github/main/assets/brand/alice-logo.svg" alt="Alice — curiouser and faster" width="480">
  </picture>
</p>

<h3 align="center">The joy of Ruby. The power of .NET.</h3>

Write expressive code with static types, compile-time safety, and the .NET libraries you already use.

```ruby
total = (1..1_000_000).map { |i| i.to_i64 * i }.select { |x| x % 2 == 0 }.sum

puts "total=#{total}"
```

- **Less ceremony.** Type inference, blocks, and pattern matching.
- **More speed.** Fused loops, SIMD, and automatic parallelization for proven-pure code.
- **Your ecosystem.** NuGet packages, ASP.NET, MonoGame, and C# interop.

**[Get started →](https://github.com/alicelanguage/alice/blob/main/docs/getting-started.md)** · [Explore examples](https://github.com/alicelanguage/alice/tree/main/samples) · [Contribute](https://github.com/alicelanguage/alice/blob/main/CONTRIBUTING.md)
