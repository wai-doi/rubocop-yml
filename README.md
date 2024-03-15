# rubocop-yml

## Usage

Add the RuboCop gems in your `Gemfile`.

```rb
# Gemfile

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
end
```

Write the `inherit_from` and URL in the `.rubocop.yml` as follow:

```yaml
# .rubocop.yml

inherit_from:
  - https://raw.githubusercontent.com/wai-doi/rubocop-yml/main/.rubocop.yml
```
