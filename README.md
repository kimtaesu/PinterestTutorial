
## [Pinterest Tutorial](https://www.raywenderlich.com/392-uicollectionview-custom-layout-tutorial-pinterest)

![](https://koenig-media.raywenderlich.com/uploads/2015/05/layout-lifecycle.png)

* `collectionViewContentSize` UICollectionView의 Width, Height 를 반환
* `prepare()` 이 메서드는 레이아웃 작업이 수행 될 때마다 호출됩니다. 콜렉션 뷰의 크기와 항목의 위치를 ​​결정하는 데 필요한 계산을 준비하고 수행 할 수있는 기회입니다.
* `layoutAttributesForElements(in:)` 이 메서드에서는 지정된 사각형 내부의 모든 항목에 대한 layout attributes을 return 합니다.
> `override func layoutAttributesForElements(in rect: CGRect) -> [UICollectionViewLayoutAttributes]?`
`layoutAttributesForItem(at:)`  `indexPath` 로 전달된 `UICollectionViewLayoutAttributes`를 return
> `override func layoutAttributesForItem(at indexPath: IndexPath) -> UICollectionViewLayoutAttributes?`
