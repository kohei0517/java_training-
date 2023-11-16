class Message1 {
  public static void main(String[] args){
    System.out.println("Good morning.");
    System.out.println("Good afternoon.");
  }
}
/*特定の文章を出力するためのプログラム。文章の行数を増やす時は上記の方法となる。

    System.out.print("Good morning.");
にすると、改行がなくなる。また、””での閉じるのは同じ行に入れること
    System.out.print("Goodmorning.\n");という形で処理をすると改行が出来る

class TextBlocksExample {
    public static void main(String[] args) {
      System.out.print("""
          Good morning.
          Good afternoon.
          goodevening.""");
    }
}
TEXTBLOCKSを利用したプログラム

class Character {
  public static void main(String[] args) {
    System.out.print('G');
    System.out.print('o');
    System.out.print('o');
    System.out.print('d');
    System.out.print(' ');
    System.out.print("morning!");
  }
}
''で囲んだ部分は「文字」として扱い、""で囲んだ部分は「文字列」として扱う

class Number1 {
  public static void main(String[] args) {
    System.out.println(1);
    System.out.println(2);
    System.out.println(3);
  }
}
数値を出力する時は””でにする必要無し。
    System.out.println(1234);
    System.out.println("1234");
だと、上はせんにひゃくさんじゅうよん、下はいちにさんしが表示されている。


/*  */で囲った部分はコメントアウト
//は行がコメントアウト
