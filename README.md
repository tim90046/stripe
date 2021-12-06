# stripe
 stripe ach
stripe payment_intents create \
  --amount=2000 \
  --currency=usd \
  -d "payment_method_types[]"=card
