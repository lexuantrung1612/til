# SEARCH unit|unit-test|testcase|unittest
assert:
  - check properties 
  - check nil
```
class ProductTest < AciveSupport::TestCase
  test "Filed cannot nil" do
    product = Product.new
    assert product.invalid?
    assert product.errors[:title].any?
  end
end
```
