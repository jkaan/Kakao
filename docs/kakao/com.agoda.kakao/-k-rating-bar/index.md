[kakao](../../index.md) / [com.agoda.kakao](../index.md) / [KRatingBar](.)

# KRatingBar

`class KRatingBar : `[`KBaseView`](../-k-base-view/index.md)`<KRatingBar>, `[`RatingBarActions`](../-rating-bar-actions/index.md)`, `[`RatingBarAssertions`](../-rating-bar-assertions/index.md)

View with RatingBarActions and RatingBarAssertions

**See Also**

[RatingBarActions](../-rating-bar-actions/index.md)

[RatingBarAssertions](../-rating-bar-assertions/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KRatingBar(function: `[`ViewBuilder`](../-view-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`)`<br>`KRatingBar(parent: Matcher<`[`View`](https://developer.android.com/reference/android/view/View.html)`>, function: `[`ViewBuilder`](../-view-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`)`<br>`KRatingBar(parent: DataInteraction, function: `[`ViewBuilder`](../-view-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [view](../-k-base-view/view.md) | `open val view: ViewInteraction` |

### Inherited Functions

| Name | Summary |
|---|---|
| [hasRating](../-rating-bar-assertions/has-rating.md) | `open fun hasRating(number: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Checks if RatingBar has number of rating as expected |
| [setRatingAt](../-rating-bar-actions/set-rating-at.md) | `open fun setRatingAt(number: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Set rating for RatingBar |
