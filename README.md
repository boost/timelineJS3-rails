# timelineJS3-rails

This gem packages the [TimelineJS3](https://github.com/NUKnightLab/TimelineJS3) for easy use with the Rails asset pipeline.

## General Installation

Add to the assets group in your Gemfile:

```ruby
gem 'timelineJS3-rails', '~> 1.0.0'
```

Install the gem:

```ruby
bundle install
```

Add the Javascript to `application.js`:


```javascript
//=require timelineJS3/timeline
```

Add the CSS to `application.css`

```css
/*
 *= require timelineJS3/timeline
 */
```

## Language

The Localization language *default is `en` English*,
if you want to change it, just add the Javascript to `application.js`:

```javascript
//=require timelineJS3/locale/xxx # you should change the xxx with one of the available
```

## Font Themes
If you want to set the font theme, just add the CSS to `application.css`:

```css
/*
 *= require timelineJS3/fonts/xxx #you should change the xxx with one of the available font themes below
 */
```

## For more detail information visit [TimelineJS3](https://github.com/NUKnightLab/TimelineJS3)

## Thanks
>- [TimelineJS3](http://timeline.knightlab.com)
