- The current template for a movie is moved into the `MovieItem.vue` component.
- The current part of the template in `App.vue` where we were looping through the movies is changed, and now it uses the `MovieItem.vue` component.
- The `notRated` value is on the `MovieItem.vue` component, as a computed property.
- The `MovieItem.vue` component accepts the `movie` as prop.
- The `MovieItem.vue` component dispatches a `edit` event with the movie `id` as param.
- The `MovieItem.vue` component dispatches a `remove` event with the movie `id` as param.
- The `MovieItem.vue` component dispatches a `update:rating` event with the movie `id` and the new `rating` as params.
- The behavior of the `updateRating` is changed to accept the movie `id` instead of the `movieIndex` .
- The behavior of the `removeMovie` is changed to accept the movie `id` instead of the `movieIndex` .
- The behavior of the `editMovie` is changed to accept the movie `id` instead of the `movieIndex` .
- The rest of our application still works as expected.
