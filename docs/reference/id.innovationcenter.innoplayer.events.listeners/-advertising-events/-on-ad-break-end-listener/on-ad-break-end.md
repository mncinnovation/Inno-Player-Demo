[reference](../../../index.md) / [id.innovationcenter.innoplayer.events.listeners](../../index.md) / [AdvertisingEvents](../index.md) / [OnAdBreakEndListener](index.md) / [onAdBreakEnd](./on-ad-break-end.md)

# onAdBreakEnd

`abstract fun onAdBreakEnd(adBreakStartEvent: `[`AdBreakEndEvent`](../../../id.innovationcenter.innoplayer.events/-ad-break-end-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Fires after the ad request and immediately before the ad is loaded into the player. Only fires before the first ad inside of an ad break.

### Parameters

`adBreakEndEvent` - The payload that accompanies the onAdBreakEnd() event.