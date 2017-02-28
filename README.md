# CHMenuView

    UITableView* t1 = [[UITableView alloc]init];
    UITableView* t2 = [[UITableView alloc]init];
    t2.backgroundColor = [UIColor lightGrayColor];
    UIView* v1 = [[UIView alloc]init];
    v1.backgroundColor = [UIColor yellowColor];
    UITableView* t3 = [[UITableView alloc]init];
    UIView* v2 = [[UIView alloc]init];
    v2.backgroundColor = [UIColor greenColor];
    
    CHMenuView* menuView = [[CHMenuView alloc]initWithFrame:self.view.frame titles:@[@"首页",@"新闻",@"资讯",@"新闻",@"资讯"] andViews:@[t1,t2,v1,t3,v2] andTitleColor:[UIColor redColor]];
