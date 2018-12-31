<div class="review">

  <div class="review-overlay" id="review-overlay-{{ review.order }}" onclick="off({{ review.order }})">
    <div class="review-text">{{ review.content }}
      <div class="review-author">&mdash; {{ review.author }}</div>
    </div>
  </div>

  <div class="review-summary" onclick="on({{ review.order }})">
    {{ review.summary }}
    <div class="review-author">&mdash; {{ review.author }}</div>
  </div>

</div>