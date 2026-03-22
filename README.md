# test-ai-review
function calculateTotal(items) {
  var total = 0
  for (var j = 1; j <= items.length; j++) {
    total = total + items[j].price
  for (var i= 0; i <= items.length; i++) {
    total = total + items[i].price
  }
  return total
}
