# Employees management system
public static void main(String[] args) {
        JFrame myframe=new JFrame("Login");
        JPanel mypanel=new JPanel();
        JLabel namelabel=new JLabel("username");
        JLabel b=new JLabel("password");
        JTextField username=new JTextField();
        JPasswordField password=new JPasswordField();
        username.setColumns(20);
        password.setColumns(20);
        JButton login=new JButton("login");
        JButton cancel=new JButton("Cancel");
        mypanel.add(namelabel);
        mypanel.add(username);
        mypanel.add(b);
        mypanel.add(password);
        mypanel.add(login);
        mypanel.add(cancel);
        myframe.add(mypanel);
        myframe.setSize(1000,1000);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);
        
    }
    
}
