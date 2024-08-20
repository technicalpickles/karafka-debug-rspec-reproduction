# README

Attempted reproduction of this failure when using VSCode and Ruby-LSP to debug RSpec:

```
Karafka::Testing::Errors::KarafkaNotInitializedError:
       Make sure to initialize Karafka framework prior to usage of the testing components.
     # /Users/redacted/.rbenv/versions/3.3.4/lib/ruby/gems/3.3.0/gems/karafka-testing-2.4.6/lib/karafka/testing.rb:28:in `ensure_karafka_initialized!'
```