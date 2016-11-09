# MyCSS


文章链接

[定制你自己的MacDown预览的css布局](http://www.jianshu.com/p/b9ceb8dac04c)


```objc
if (i == 100) {
  NSLog(@"123");
  self.btn = nil;
  UIButton *btn = [UIButton new];
}

- (void)test:(UIButton *)button {
    if (!self.button) {
        self.button = button;
        [self test:button];
    }
}

```

```objc
- (void)jx_insertionSortUsingComparator:(JXSortComparator)comparator didExchange:(JXSortExchangeCallback)exchangeCallback {
    if (self.count == 0) {
        return;
    }
    for (NSInteger i = 1; i < self.count; i ++) {
        for (NSInteger j = i; j > 0 && comparator(self[j], self[j - 1]) == NSOrderedAscending; j --) {
            [self jx_exchangeWithIndexA:j indexB:j - 1 didExchange:exchangeCallback];
        }
    }
}
```
