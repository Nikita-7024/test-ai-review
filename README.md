# test-ai-review
function calculateTotal(items) {
  var total = 0
  for (var j = 0; j <= items.length; j++) {
    total = total + items[j].price
  }
  return total
}
