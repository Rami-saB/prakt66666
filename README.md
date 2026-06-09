xmlns:local="clr-namespace:Praktika6"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition />
            <ColumnDefinition />
            <ColumnDefinition />
        </Grid.ColumnDefinitions>
        <Grid.RowDefinitions>
            <RowDefinition Height="3*"/>
            <RowDefinition Height="1*"/>
            <RowDefinition Height="1*"/>
            <RowDefinition Height="2*"/>
        </Grid.RowDefinitions>
        <TextBlock Grid.Column="1" VerticalAlignment="Bottom" HorizontalAlignment="Center" FontSize="24" FontWeight="Bold">РЕГИСТРАЦИЯ</TextBlock>
        <StackPanel Grid.Column="1" Grid.Row="1" Margin="0,10,0,0">
            <TextBlock Margin="0,0,0,5">Логин</TextBlock>
            <TextBox></TextBox>
        </StackPanel>
        <StackPanel Grid.Column="1" Grid.Row="2" Margin="0,10,0,10">
            <TextBlock Margin="0,0,0,5">Пароль</TextBlock>
            <TextBox></TextBox>
        </StackPanel>
        <Button Grid.Column="1" Grid.Row="3" HorizontalAlignment="Center" VerticalAlignment="Top" Background="LightGreen" Padding="30,10,30,10">Зарегаться</Button>
    </Grid>
</Window>
