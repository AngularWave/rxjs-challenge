# RxJS Challenge
A set of little RxJS puzzles to practice your Observable skills by [Alex](https://twitter.com/Waterplea) and [Roman](https://twitter.com/marsibarsi).

## Day 01
Create an Observable to track focus in a section of the page.

- [Template](https://stackblitz.com/edit/rxjs-challenge-01)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-01-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-01-tracking-focus-within-page-section-a920bdebe4ef?source=friends_link&sk=b6454a6347b045a4684bef86d218d2f9)

## Day 02
Create a page visibility stream.

*Additional Angular task:* make it a global DI injection token.

- [Template](https://stackblitz.com/edit/rxjs-challenge-2)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-2-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-02-creating-a-page-visibility-stream-adf829324eb1?sk=cf4d27f8a40367d0b1ea2542974ec57f)

## Day 03
Show error message for 5 seconds if login has failed.

*Bonus task:* show user name instead of button upon successful login and disable button during server request.

- [Template](https://stackblitz.com/edit/rxjs-challenge-03)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-03-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-03-showing-error-message-for-a-period-of-time-15b428d49315?sk=5c0907b3827fc6270429796ec530ee76)

## Day 04

Make a loading with progress bar until result.

- [Template](https://stackblitz.com/edit/rxjs-challenge-4)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-4-solution)
- [Article](https://medium.com/angularwave/lets-make-loading-with-progress-bar-until-result-rxjs-challenge-04-f638d3cfc539?sk=e5ab427bc7fd33d4843185f1686a359b)

## Day 05

Create a countdown and a button to restart it.

- [Template](https://stackblitz.com/edit/rxjs-challenge-05)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-05-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-5-making-a-countdown-6cd6171685cb?sk=11f7f0616bae33a270247cf48c9a590c)

## Day 06

Write a stream of selected seats for users of cinema website.

- [Template](https://stackblitz.com/edit/rxjs-challenge-6)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-6-solution)
- [Article](https://medium.com/angularwave/rxjs-ng-challenge-6-picking-cinema-seats-8d73dbaadcea?sk=11eaf62c8ce3faf5392abf4e5d0b3495)

## Day 07

Make a sticky header that disappears when you scroll down and re-appears when you scroll up.

- [Template](https://stackblitz.com/edit/rxjs-challenge-07)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-07-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-7-disappearing-sticky-header-b7689c23bf66?sk=8d4e3385925b110a207e978d0ed6a190)

## Day 08

Make a sticky header that disappears when you scroll down and re-appears when you scroll up.

- [Template](https://stackblitz.com/edit/rxjs-challenge-8)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-8-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-8-smart-search-operator-function-e619bee10392?sk=105ce13efe946593d252557164dfb7a8)

## Day 09

Make subtitles appear in pairs for a karaoke game.

- [Template](https://stackblitz.com/edit/rxjs-challenge-09)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-09-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-09-karaoke-subtitles-39cc5c133746?sk=156ec25cc123491bd299694f7484e12c)

## Day 10

Make a color picker.

- [Template](https://stackblitz.com/edit/rxjs-challenge-10)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-10-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-10-color-picker-palette-71e99e28b400?sk=1f624b2be951544a2399865c52f9366f)

## Day 11

Make a toast notification disappear in 3 seconds unless user holds cursor over it

- [Template](https://stackblitz.com/edit/rxjs-challenge-11)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-11-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-11-auto-close-notification-23910ea53218?sk=d7ad0a1f5dee2297a5d1181c58192e79)

## Day 12

Make a modal close on Esc key and by clicking outside.

*Important*: only clicks that both started and ended outside count! 

- [Template](https://stackblitz.com/edit/rxjs-challenge-12)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-12-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-12-modal-closing-4c01884db556?sk=6fe05ac705672468ddd257263224f5e1)

## Day 13

Make a sticky header that shrinks proportionally when you scroll down. 
A common pattern for mobile devices so header takes less screen estate when page is scrolled.

- [Template](https://stackblitz.com/edit/rxjs-challenge-13)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-13-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-13-shrinking-header-72fc672a5b6a?sk=6501dd68073698c3bb0869a653ad5e57)

## Day 14

You have an area with folders. Allow user to select several folders dragging their mouse (like on desktop).

- [Template](https://stackblitz.com/edit/rxjs-challenge-14)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-14-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-14-select-folders-d1838087ba47?sk=698d4e240f0a186eb20b972ba15827c4)

## Day 15

Determine whether an element was focused with keyboard, mouse, touch or programmatically

- [Template](https://stackblitz.com/edit/rxjs-challenge-15)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-15-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-15-tracking-focus-type-aa8309f52bc1?sk=d9f84ac05cc25d704ad071f8d6c111bf)

## Day 16

There is a picture in some preview app and logic that handles user events and collect them in three streams: drag$, rotation$ and zoom$. 

Make an RxJS stream that will transform a picture inside zone according to drag events, rotation and zoom

- [Template](https://stackblitz.com/edit/rxjs-challenge-16)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-16-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-16-image-viewer-30cf01d61f0a?sk=59dcb0b698d2ab62f436b7b00b79a612)

## Day 17

Create a no-flicker loading message (if loading took < 1 sec. do not show it, if loading took > 1 sec. show it for at least 1 sec).

- [Template](https://stackblitz.com/edit/rxjs-challenge-17)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-17-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-17-non-flicker-loader-15545d3be525?sk=35996e885123bc2881ec61288a5b47eb)


## Day 18

Imitate native iOS and Android pull-to-refresh behavior.

- [Template](https://stackblitz.com/edit/rxjs-challenge-18)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-18-solution)
- [Article](https://medium.com/angularwave/rxjs-and-angular-pull-to-refresh-that-emulates-native-ios-and-android-rxjs-challenge-18-75408c53f66?sk=a527a38925c1bbb0e623fd6169faa7d0)


## Day 19

Create Observable based on requestAnimationFrame and show FPS meter.

- [Template](https://stackblitz.com/edit/rxjs-challenge-19)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-19-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-19-fps-meter-a44383e2bd6d?sk=5b25c343f2cb793431a166f5d09e9db9)


## Day 20

Recreate classic Material Design ripple effect.

- [Template](https://stackblitz.com/edit/rxjs-challenge-20)
- [Solution](https://stackblitz.com/edit/rxjs-challenge-20-solution)
- [Article](https://medium.com/angularwave/rxjs-challenge-20-ripple-68b62a77fba8?sk=f31d29e8d8c5bd3b311dc59d64ac6217)
