ModalLearning

=============

利用Modal形式展示控制器

[self presentViewController:controllerName animated:YES completion:^{
    NSLog(@"展示完毕");
}];

关闭modal控制器

[self dismissViewControllerAnimated:YES completion:nil];

切换控制器

1.UINavigationController

2.UITabBarController（不常用）

3.Modal
